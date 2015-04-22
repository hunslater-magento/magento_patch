MMind_Magento_Patch
==================

Magento Patch Collection.
Each branch contains the patch for the specific bug.

# Patch SUPEE-533

Addresses a potential remote code execution exploit. - Added Feb 9, 2015

# Branch

- supee-5344

# How to Apply

Please upload the patch into your Magento root directory and run the appropriate SSH command:
For patch files with the file extension .sh:
sh patch_file_name.sh
Example: sh PATCH_SUPEE-1868_CE_1.7.0.2_v1.sh
For patch files with the file extension .patch:
patch –p0 < patch_file_name.patch
Once that is done, refresh the cache in the Admin under "System > Cache Management" so that the changes will be reflected. We highly recommend you test all patches in a test environment before taking them live. 