MMind_Magento_Patch
==================

Magento CE 1.x Patch Collection.<br />
Each branch contains the patch for the specific bug.

# Patch SUPEE-6285

This patch provides protection against several types of security-related issues, including information leaks, request forgeries, and cross-site scripting.<br />
Make sure to install SUPEE-5994 patch first. Magento Community Edition version 1.9.2 already includes the latest version of the patch. More information about the individual issues addressed by this patch is available in the patch [release notes](http://merch.docs.magento.com/ce/user_guide/Magento_Community_Edition_User_Guide.html#magento/patch-releases-2015.html).

# Branch

- supee-6482 (04 August 2015)
- **supee-6285**
- supee-6237
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