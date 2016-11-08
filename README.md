# WT101

Basic project demonstrating usage of HTML, CSS, JavaScript, MySQL and PHP designed for UE15CS208 course, PESU. Three simple games are embedded into the project. All the game revolve around guessing of colors. 

One game lets the user decide the difficulty by allowing the user to be in control of the number of options to choose from. We will have one correct color displayed in RGB format and 'n' option tiles (based on user's choice) out of which 1 tile will match the correct option. 

Another game will have predefined levels of difficulty. Starting from level 1 where the user chooses the correct one from two options to level 8 where the user has 9 options to choose from.

The third game will pull a color from the database and ask the user to guess the name of the color

## Prerequisites

* Apache (Or equivalent local web server)
* A compatible browser (Some functions won't work fine/ are not optimized for IE8 and Edge)
* mysql
* php5/7 (Most functions mostly work with both, tested thorougly on PHP7)

## Usage

1. Transfer all the files either by downloading and extracting or clone to /var/www/html/public_html (or equivalent).
2. Take the <b>```databasedump.sql```</b> and put it in a folder that is accessible.
4. You can import the database using ```phpmyadmin```
3. Run the following in terminal (or equivalent) if you do not prefer to use ```phpmyadmin```:


```
    mysql -u USERNAME -p colorListFinal < file/path/databasedump.sql
```

## Structure

* All the stylesheets, fonts, javascripts, videos, etc used in the making of the project have been stored in the ```assets``` folder.

* All Stylesheets and JS are in assets/stylesheets and assets/JS/. They carry the same name as that of the .html/.php file.



## Testing

The project has been tested for various environments on <b>Ubuntu 16.04</b>, with <b> Apache Webserver </b> on <b> Google Chrome</b> and <b> Mozilla Firefox </b>

***

A project by Rohan Mallya (01FB15ECS239) & Paridhi Sinha (01FB15ECS203)
