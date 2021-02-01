# Tybalt

## About Tybalt

Tybalt is TBT Engineering's first internal software project. At the moment its major feature is a way for staff to enter time sheets and for administration to make payroll reports and invoicing reports using the structured data generated from the time sheets. The software is web-based (it works in modern web browsers), can be accessed using everyone's existing username and password (protected by MFA and optionally passwordless using the Microsoft Authenticator), and is created mobile-first, meaning it's fully featured on your phone! Over time as business processes that can be automated are discovered, Tybalt will be updated to integrate other parts of the company.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/home.png">
</p>

## Recording time

The way most staff will used Tybalt most of the time is for their time sheets. Previously, staff had to enter time sheets manually on an Excel spreadsheet and send them to a central email address where each entry was manually verified. The time sheet entries were subsequently collated to create an invoicing report and then sent to payroll where employees could be paid based on the content. Tybalt improves every part of this process. Here's how that works.

### 1. Time Entries

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/createEntry.png">
</p>

Time entries are the most basic unit of time. They contain a single description of an event that an employee worked on. Validations are run on each time entry every time they're saved helping to minimize errors. Think of time entries is as individual rows of the old time sheet system. Tybalt introduces some benefits. You can set a default division so it is automatically selected each time you make a time entry. Job numbers can only be entered if they already exists in tybalt. This ensures that you aren't accidentally making up jobs that don't exist! Fields that aren't allowed for a given time type are hidden when you select that time type. For example, if you've selected PPTO you won't be able to enter job hours. More checks will be added in the future to speed your workflow.

### 2. Bundling a Time Sheet

Time sheets are not manually created. Instead, at the end of a week when you've created all of your time entries, you bundle them together into a time sheet by clicking the bundle ![Bundle](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/bundleIcon.png) icon. There can only be one time sheet for a given week so if you need to edit a time sheet, you must unbundle it (by clicking the Edit ![Edit](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/editIcon.png) icon), edit ![Edit](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/editIcon.png) or delete ![Delete](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/deleteIcon.png) the entry or add others, then rebundle it. This process exists because validations are done on a time sheet *as a whole* during the bundling process. For example, if you've tried to bank overtime but that brings your total below 44 hours, the bundling step will fail. Lots of these checks exist, but in reality they're just automating the rules that were already in place when we used to use Excel spreadsheets.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/bundle.png">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/bundling.png">
</p>

### 3. Submitting a Time Sheet

Once you have created a time sheet by bundling your time entries, it needs to be submitted to your manager for approval. You choose your manager in settings in the same way you choose your default division. If you change your manager you'll be logged out so the settings take effect. You only need to set your manager once unless your reporting manager changes.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/tybalt-images/submitEdit.png">
</p>

Submitting the time sheet is done with one click on the paper airplane ![Submit](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/submitIcon.png) icon. If you submit your time sheet and then realize you've made a mistake, as long as your manager hasn't already approved it, you can recall it. You do this by clicking the rewind ![Recall](https://github.com/stamler/tbte-docs/blob/master/tybalt-images/recall.png) icon. If your manager has already approved it and administration hasn't already locked the time sheet for running payroll and invoicing, you can ask your manager to reject the time sheet. Once this is done you must recall the rejected time sheet and unbundle it then bundle it again before it can be resubmitted to your manager. If your time sheet was approved and locked and you later discover there were errors or omissions, you must submit a manual amendment request on a spreadsheet. Amendments are entered by administrators and because of their retroactive nature are represented in reports for the week they were entered rather than for the week the time was accrued in.