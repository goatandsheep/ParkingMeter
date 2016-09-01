ParkingMeter
============

Introduction
------------

A group design project of a parking meter for school. The parking meter allows the user to be able to insert currency and prints out a receipt placed on the car dashboard. This was built using a website builder, called [axure](http://www.axure.com/). [See the design here](https://goatandsheep.github.io/ParkingMeter/).

Course: SFWR ENG 4HC3

Using
-----

* Commit your project file, i.e. `main.rp` in the `main` branch
* The folder you export your html to should be your git directory, i.e. path(git dir) = path(export dir)
* Commit the HTML to the `gh-pages` branch

Refund
-------

* Home: need language page names from Kevin
* Scan:
	* need to `setTimeout(change display, 1000ms);` after moving the receipt up, down
	* Make change slot background beige on confirming refund
	* Make change slot background back to grey after clicking on it
* Print:
	* prints the receipt. To print, say `document.getElementsByName("receipt")[0].innerHTML+="Whatever you want to print on the receipt";`
	* Need to figure out how to make the screen a sidebar
