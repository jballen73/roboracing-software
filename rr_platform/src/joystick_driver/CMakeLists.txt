add_executable(${PROJECT_NAME}_joystick_driver joystick_driver.cpp)
target_link_libraries(${PROJECT_NAME}_joystick_driver ${catkin_LIBRARIES})
add_dependencies(${PROJECT_NAME}_joystick_driver rr_platform_generate_messages_cpp)
set_target_properties(${PROJECT_NAME}_joystick_driver PROPERTIES OUTPUT_NAME "joystick_driver")
