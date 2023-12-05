This is intended for use with the encp_test_script_no_dcache script which ships along with Enstore, found at: https://github.com/Enstore-org/enstore/blob/develop/tools/encp_test_script_no_dcache

To use this repo on an enstore machine:

1. Copy or symlink $ENSTORE_DIR/tools/encp_test_script_no_dcache to this root directory
1. Run ./generate_files to create the needed test files
1. Make pnfs dir (mkdir /pnfs/fs/usr/data/renbauer/LTO8/ACCT/$ENSTORE_VERSION)
1. Set LOCAL_DIR and PNFS_DIR (TODO)
1. Run the encp_test_script_no_dcache script (as enstore user)
1. Use ./clean_files to delete the test files
