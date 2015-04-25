MMind_Magento_Patch
==================

Magento CE 1.x Patch Collection.
Each branch contains the patch for the specific bug.

# Patch

This patch addresses the USPS API changes that went effective on Sep. 7th.<br />
Added Sep 23, 2014
Note: For versions earlier than Magento Community Edition 1.9.x, the new patches need to be installed on previous USPS patch (SUPEE-1868) issued in 2013.<br /> 
Please make sure the patch SUPEE-1868 is installed first. 

# Branch

- supee 4921-4334

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