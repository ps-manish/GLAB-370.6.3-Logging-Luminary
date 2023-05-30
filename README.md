# GLAB-370.6.3-Logging-Luminary

## Welcome to the "Logging Luminary: Mastering Logging at Different Severity Levels" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on an exciting coding adventure that focuses on **logging** at different severity levels using the `logging` module in Python. Get ready to become a luminary of logging and effectively manage log messages in your applications!

### Prerequisites

Before we begin, make sure you have the following:

- Basic knowledge of Python syntax.
- A Python interpreter or an integrated development environment (IDE) installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: Understanding Logging](#step-2-understanding-logging)
- [Step 3: Logging at Different Severity Levels](#step-3-logging-at-different-severity-levels)
- [Step 4: Configuring Logging](#step-4-configuring-logging)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's begin our adventure into the world of logging. Logging is a crucial practice in software development that involves recording log messages to provide information about the execution of your application. In this lab, we'll learn how to log messages at different severity levels to manage and troubleshoot our applications effectively.

### Step 2: Understanding Logging

Before diving into logging at different severity levels, let's understand the concept of logging. Logging is the process of generating log messages to record events, activities, or errors that occur during the execution of an application. Log messages serve as a valuable source of information for monitoring, debugging, and troubleshooting applications.

### Step 3: Logging at Different Severity Levels

The `logging` module in Python provides various severity levels for logging messages, ranging from the most critical to the least critical. These severity levels help categorize log messages and provide a structured way to manage and prioritize log information.

The standard severity levels in the `logging` module include:

- `CRITICAL`: Critical errors that lead to application failure.
- `ERROR`: Errors that impact the functionality of the application.
- `WARNING`: Warnings that indicate potential issues or unexpected behavior.
- `INFO`: Informational messages about the progress or status of the application.
- `DEBUG`: Detailed debugging information that helps diagnose issues.
- `NOTSET`: The lowest severity level, used to enable all log messages.

To log messages at different severity levels:

1. Import the `logging` module at the top of your Python file.
2. Configure the logging system, including the desired log level and output format.
3. Use the appropriate logging method (`logging.critical()`, `logging.error()`, `logging.warning()`, `logging.info()`, `logging.debug()`) to log messages at the corresponding severity level.
4. Run your application and observe the logged output, ensuring that the log messages reflect the appropriate severity levels.

### Step 4: Configuring Logging

To configure the logging system, you can use the following steps as a starting point:

```python
import logging

# Configure the logging system
logging.basicConfig(
    level=logging.DEBUG,
    format='%(asctime)s - %(levelname)s - %(message)s'
)

# Log messages at different severity levels
logging.critical('This is a critical message')
logging.error('This is an error message')
logging.warning('This is a warning message')
logging.info('This is an informational message')
logging.debug('This is a debug message')
```

In this example, we configure the logging system to log messages at the `DEBUG` level and set a specific format for the log messages. We

 then use different logging methods to log messages at different severity levels.

### Step 5: Challenge

Now it's time for an exciting challenge! Take a piece of your code and add logging statements at different severity levels to manage and track the execution and behavior of your application effectively. Experiment with different log levels and explore the impact of changing the log level configuration.

### Step 6: Conclusion

Congratulations on completing the "Logging Luminary: Mastering Logging at Different Severity Levels" Guided Lab! You've learned how to log messages at different severity levels using the `logging` module in Python and effectively manage log information in your applications.

Remember to leverage logging strategically to provide valuable insights into the execution of your applications. Logging helps with monitoring, debugging, and troubleshooting, ensuring the reliability and stability of your software.

Feel free to reach out if you have any questions. Happy logging, and may your log messages illuminate the path to success! 🎉
