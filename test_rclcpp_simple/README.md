
## How to Compile:
```
colcon build --packages-select test_rclcpp_simple
```

## How to Run:
### without verbose output:
```
colcon test --packages-select test_rclcpp_simple
```  
### with verbose output:
```
colcon test --event-handlers console_direct+ --packages-select test_rclcpp_simple
```
### check the return status:
```
colcon test-result --test-result-base build/test_rclcpp_simple
echo $?
```
