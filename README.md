# Table of Contents
1. [Introduction to PowerShellGet](#exercise-introduction-to-powershellget)
  1. [Install a module](#task-install-a-module)
  1. [Install a module - solution](#task-install-a-module---solution)

# EXERCISE Introduction to PowerShellGet

PowerShellGet is an extension of the Package Management feature in Windows PowerShell that facilitates the distribution and management of PowerShell modules. In this exercise, you will learn how to install and update modules that are available to PowerShellGet via the PowerShell Gallery.

## INTRODUCTION CONTENT URL

http://learnondemandsystems.com/

## COMPLETION MESSAGE

Thank you for taking this lab. We hope you learned a lot!

## COMPLETION CONTENT URL

http://learnondemandsystems.com/

### TASK Install a module

Using PowerShellGet, find and install the **ProtectedData** module for all users.

#### :warning: ALERT

#### :bulb: KNOWLEDGE

Hint #1: Installing modules for all users with PowerShellGet requires elevation.

Hint #2: The verbs for the commands you need can be found in the instructions for this task.

If you get stuck, review the video again, paying close attention to the list of commands that are shown near the end -- the command that you need to use can be found in that list.

If you're really stuck and just can't figure it out, click Done and the video in the next task will show you how this task can be completed.

#### :camera: SCREENSHOT

![New user table](https://github.com/LearnOnDemandSystems/skunkworks-02-lab/blob/master/screenshots/NewUserTable.png)
```
ShowAutomatically = No|Once|EveryTime
```

#### :movie_camera: VIDEO

```
Uri = https://github.com/LearnOnDemandSystems/skunkworks-02-lab/blob/master/videos/01-intro.mp4
ShowAutomatically = No|Once|EveryTime
ShowInDialog = false
```

#### :calling: COMMAND [PowerShell|PowerShellWithUI|Shell|ShellWithUI|TypeText]

```PowerShell
Find-Module ProtectedData | Install-Module
```

#### :computer: ACTIONS

```
VM = NoAction|VMName
FloppyDrive = NoAction|FloppyName|Eject
DVDDrive = NoAction|DVDName|Eject
```

### TASK Install a module - solution

Click the **video camera** icon to view the solution, or click **Done** to continue with the next task.

#### :warning: ALERT

#### :bulb: KNOWLEDGE

If you would like the solution entered for you, place your cursor at the PowerShell prompt and click on the **caret** icon.

#### :camera: SCREENSHOT

![New user table](https://github.com/LearnOnDemandSystems/skunkworks-02-lab/blob/master/screenshots/NewUserTable.png)
```
ShowAutomatically = No|Once|EveryTime
```

#### :movie_camera: VIDEO

```
Uri = http://learnondemandsystems.com/video.mp4
ShowAutomatically = No|Once|EveryTime
ShowInDialog = false
```

#### :calling: COMMAND [PowerShell|PowerShellWithUI|Shell|ShellWithUI|TypeText]

```PowerShell
Find-Module ProtectedData | Install-Module
```

#### :computer: ACTIONS

```
VM = NoAction|VMName
FloppyDrive = NoAction|FloppyName|Eject
DVDDrive = NoAction|DVDName|Eject
```
