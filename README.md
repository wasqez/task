# Installation

#Run

`git clone git@github.com:wasqez/task.git project`

#Install module 

`git submodule update --init`

#Install Drupal

`composer install`

## Run Drupal

Run Drupal from Acquia DevDesktop.
Need to select root folder: project/web

> Note: Run Drupal installation at standard profile.

## Config

Go to Drupal Administration Extend and enable Simple lexer parser module. 

Select Content types Article fields page:

*admin/structure/types/manage/article/fields*

*add field type as text (formatted)*

*Field name: Math*

Go to Manage Display tab:

*Select from "FORMAT" drop down menu "Simple lexer parser formatter"

*Drag to re-order "Math" field on top of the row.*

*Press Save*

## Usage

Add new content Article 

Add Title and test math operation in Math field.

(+,-,*,/)

Save 


On Default Display of saved Article do mouse hover math label to se the results.
