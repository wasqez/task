# Installation

#Run

`git clone git@github.com:wasqez/task.git project`

#Install module 

`git submodule update --init`

#Install Drupal

`composer install`

## Usage

Run Drupal from Acquia DevDesktop.
Need to select root folder: project/web

> Note: Run Drupal installation at standard profile.

## Config and usage

Go to Drupal Administration and select Content types Article fields page.

*admin/structure/types/manage/article/fields*
*add field type as text (formatted)*
*Field name: Math*

Go to Manage Display tab.
*Select from "FORMAT" drop down menu "Simple lexer parser formatter"
*Drag to re-order "Math" field on top of the row. 
*Pres Save

Add new content Article 
Add Title and test math operation in Math field.
(+,-,*,/)
Save 

On Default Display do mouse hover to se result.


