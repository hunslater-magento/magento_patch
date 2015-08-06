MMind_Magento_Patch
==================

Magento CE 1.x Patch Collection.<br />
Each branch contains the patch for the specific bug.<br />
There are also a branch for a single version of Magento with all patches you need.

# Patch Branch

- supee-6482 (04 August 2015)
- supee-6285 
- supee-6237 (18 June 2015)
- supee-5994
- supee-5344
- supee-4829
- supee-1533
- supee-4291-4334
- supee-1868
- supee-3941
- supee-3762
- supee-2725
- php-54
- appsec-212

# Magento Version Branch

- 1.9.2.0

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