set( TEST_DIRECTORY ${PROJECT_SOURCE_DIR}/test )
include( ${TEST_DIRECTORY}/AddTestHelpers.cmake )

set( SUB_DIR_NAME subdir )

## テストケースの追加
create_test_case( ${SUB_DIR_NAME}/test_file_name_appended_extension )
