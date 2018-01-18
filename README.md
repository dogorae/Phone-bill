# Phone bill

There are three people in my Verizon plan, and we split the bill. I'm tired of manually calculating phone bills for each person every month.

The goal of this project is to automatically split the bill and notify people by email two days before the due date.

## Purposes of this project
* Force myself to do some coding
* It would be actually quite nice if this can be implemented. Splitting the bill is a monthly nuisance.
* Get used to using the git workflow
* Learn GUI with Tkinter (although it would be totally unnecessary for the project itself)

## Plan of attack
* Retrieve phone bill and split it
  1. Find a way to deal with authentication
  2. Retrieve the bill in pdf format (find an alternative method if possible)
  3. Go to the end of the bill, where Verizon kindly splits the bill
  4. Do some trivial calculation to split the $50 data fee
* Make some GUI
  1. If possible, display the pdf bill
  2. Show the splitted bill
  3. Make a button that sends email
  4. Save the bill to some directory for the records

## Relavent or (potentially) useful websites
[Verizon Wireless](https://www.verizonwireless.com/)

[Tkinter tutorial](https://www.lynda.com/Tkinter-tutorials/Python-GUI-Development-Tkinter/163607-2.html)