add_executable(test_mxb_log test_log.cc)
target_link_libraries(test_mxb_log maxbase rt)
add_test(test_mxb_log test_mxb_log)

add_executable(test_semaphore test_semaphore.cc)
target_link_libraries(test_semaphore maxbase pthread rt)
add_test(test_semaphore test_semaphore)

add_executable(test_worker test_worker.cc)
target_link_libraries(test_worker maxbase pthread rt)
add_test(test_worker test_worker)
