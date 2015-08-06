MMind_Magento_Patch
==================

Magento Patch Collection.
Each branch contains the patch for the specific bug.

# Patch SUPEE-5994

This patch addresses multiple security vulnerabilities in Magento Community Edition software, including issues that can put customer information at risk. - Added May 14, 2015 

# Branch

- supee-6482 (04 August 2015)
- supee-6285
- supee-6237
- supee-5994

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
