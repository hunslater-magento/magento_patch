MMind_Magento_Patch
==================

Magento CE 1.x Patch Collection.<br />
Each branch contains the patch for the specific bug.<br />
There are also a branch for a single version of Magento with all patches you need.

<<<<<<< HEAD
# Patch

This patch addresses the USPS API changes that went effective on Sep. 7th.<br />
Added Sep 23, 2014
Note: For versions earlier than Magento Community Edition 1.9.x, the new patches need to be installed on previous USPS patch (SUPEE-1868) issued in 2013.<br /> 
Please make sure the patch SUPEE-1868 is installed first. 

# Branch

- supee 4921-4334
=======
# Patch Branch

- supee-6482 (04 August 2015)
- supee-6285 (07 July 2015)
- supee-6237 (18 June 2015)
- supee-5994 (14 May 2015)
- supee-5344 (09 February 2015)
- supee-4829 (26 November 2014)
- supee-1533 (03 October 2014)
- supee-4291-4334 (23 September 2014)
- supee-1868 (23 September 2014)
- supee-3941 (12 August 2014)
- supee-2725 (12 February 2014)
- php-54 (17 January 2014)
- appsec-212 (17 January 2014)

# Magento Version Branch

- 1.9.2.1
- 1.9.2.0
- 1.9.1.1
- 1.9.1.0
- 1.9.0.1
- 1.9.0.0
- 1.8.1.0
- 1.8.0.0
- 1.7.0.2
- 1.7.0.1
- 1.7.0.0
- 1.6.2.0
- 1.6.1.0
- 1.6.0.0
- 1.5.1.0
- 1.5.0.1
- 1.4.2.0
- 1.4.1.1
- 1.4.1.0
- 1.4.0.1
- 1.4.0.0
>>>>>>> master

# How to Apply

Please upload the patch into your Magento root directory and run the appropriate SSH command:<br />
**For patch files with the file extension .sh:** 

<pre>
sh patch_file_name.sh
</pre>

Example: 
<pre>
sh PATCH_SUPEE-1868_CE_1.7.0.2_v1.sh
</pre>

**For patch files with the file extension .patch:**

<pre>
patch –p0 < patch_file_name.patch
</pre>

Once that is done, refresh the cache in the Admin under "System > Cache Management" so that the changes will be reflected.<br />
We highly recommend you test all patches in a test environment before taking them live.