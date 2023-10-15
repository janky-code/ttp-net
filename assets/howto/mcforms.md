# Introduction to MCForms

## What are MCForms?
Basically it is a Multiple Choice Form (MCForms). The form collects the
assigned value to answer options provided. The form populates an alpha or numerical values into the message for transmittal.
With MCForms, a message would consist of values such as "13241" which map to the answers selected in the dropdown menu.
This allows for uniformity of messages and drastically reduces the amount of resources necessary to transmit. 
If a preselected answer does not exist, some fields contain an [Expect Statement]().


**ELI5**: - If a form contains the question "What is the weather", dropdown
options may be something like: 

- 1 sunny 
- 2 rain 
- 3 hurricane

Selecting rain would only require transmitting the number "2" as opposed
to "rain".

## Where do I put them?
The test files begenning with MCF should be placed in the forms directory where js8spotter was installed. On windows that would be `C:\js8spotter-<version number>\forms`.

## How do I use them?
### Transmitting a form
In JS8Spotter, click `Tools > MCForms - Forms` then click on the form you intend to use. All TTP forms are formatted as `F!4XX TTP <FORM NAME>`

### Reading a form
