# Tybalt

## About Tybalt

Tybalt is TBT Engineering's first internal software project. At the moment its major feature is a way for staff to enter timesheets and for administration to make payroll reports and invoicing reports using the structured data generated from the timesheets. The software is web-based (it works in modern web browsers), can be accessed using everyone's existing username and password (protected by MFA and optionally passwordless using the Microsoft Authenticator), and is created mobile-first, meaning it's fully featured on your phone! Over time as business processes that can be automated are discovered, Tybalt will be updated to integrate other parts of the company.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/home.png">
</p>

## Recording time

The way most staff will used Tybalt most of the time is for their timesheets. Previously, staff had to enter timesheets manually on an Excel spreadsheet and send them to a central email address where each entry was manually verified. The timesheet entries were subsequently collated to create an invoicing report and then sent to payroll where employees could be paid based on the content. Tybalt improves every part of this process. Here's how that works.

### 1. Time Entries

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/createEntry.png">
</p>

These are the most basic unit of time. They contain a single description of an event that an employee worked on. Basic validations are run on each time entry every time they're saved helping to minimize errors. The easy way to think about time entries is as individual rows of the old timesheet system. Tybalt introduces some interesting benefits. Firstly, you can have a default division so this is automatically selected each time you make a time entry. Secondly, you can only enter a job number that already exists in the tybalt. This ensures that you aren't accidentally making up jobs that don't exist! Third, fields that aren't allowed for a given time type are hidden when you select that time type. For example, if you've selected PPTO you won't be able to enter job hours. More checks will be added in the future to speed your workflow.

### 2. Bundling a Time Sheet

Timesheets cannot be created manually. They are always created by bundling together time entries. At the end of a week when you've created all of your time entries, you bundle them together into a TimeSheet. There can only be one timesheet for a given week so if you need to edit a timesheet, you must unbundle it (by clicking the Edit icon), edit, delete or create the entries, then rebundle it. This process exists because validations are done on a timesheet *as a whole* during the bundling process. For example, if you've tried to bank overtime but that brings your total below 44 hours, the bundling step will fail. Lots of these checks exist, but in reality they're just automating the rules that were already in place when we used to use Excel spreadsheets.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/bundle.png">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/bundling.png">
</p>

### 3. Submitting a Time Sheet

Once you have created a time sheet by bundling your time entries, it needs to be submitted to your manager for approval. You choose your manager in settings in the same way you choose your default division. If you change your manager you'll be logged out so the settings take effect. You only need to set your manager once unless your reporting manager changes.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/submitEdit.png">
</p>

Submitting the timesheet is done with one click on the paper airplane icon. If you submit your timesheet and then realize you've made a mistake, as long as your manager hasn't already approved it, you can recall it. ![Recall](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/recall.png) You do this by clicking the rewind icon. If your manager has already approved it and administration hasn't already locked the timesheet for running payroll and invoicing, you can ask your manager to reject the timesheet. Once this is done you must recall the rejected timesheet and unbundle it then bundle it again before it can be resubmitted to your manager. If your timesheet was approved and locked and you later discover there were errors or omissions, you must submit a manual amendment request on a spreadsheet. Amendments are entered by administrators and because of their retroactive nature are represented in reports for the week they were entered rather than for the week the time was accrued in.