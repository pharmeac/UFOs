# UFOs

## Overview
The purpose of this build was to provide the user the ability to refine their search parameters to get a more in-depth analysis of UFO sightings. We did this by building out the webpage source files to allow additional filters for city, state, country, and shape of UFO sitings. This was in addition to the original date filter.

## Results
Here is a walkthrough on how the website appears to the end user, and how they can use the filters to narrow down the UFO sitings to those they are interested in.
### Initial webpage load
The initial load of the webpage loads the full table data of all UFO sitings on the right hand side. On the left, are the available filters that the user can utilize to narrow in on the UFO sitings they are interested in.
![image](https://user-images.githubusercontent.com/109913335/201487117-2d87d9b3-63ae-4add-8705-e8e3c9811505.png)
### Entering information into the filters
To filter the results shown on the page, the user simply clicks into one of the filters, i.e."Enter a City", types what the filter text "i.e. bonita", then hits the ENTER key. Once the ENTER key is hit, the table on the page is filtered to records that meet that filter criteria.
![image](https://user-images.githubusercontent.com/109913335/201487334-ed76bd87-5f05-4411-99c8-39d288acab0d.png)

### Multiple filters can be selected
The user can enter information into multiple filters to really drill down to those records they are interested in. For example, a user can enter a State (i.e. "ca") and a Shape (i.e. "light").
![image](https://user-images.githubusercontent.com/109913335/201487424-77289b3d-f81d-444e-8cd6-0f8ff9852ab1.png)

### Clear the filters
To clear the filters, the user deletes the data in each of the filters, then again hits the enter key. The table data will return to the full data shown on the initial load of the webpage.

## Summary
### Drawbacks
One drawbeck to the current build is that the data is not formatted in a standard way. For example, the city, state, and country values are all lowercase. Entering a filter that capitalizes one of these values does not match on records in the table. Additionally, the date field should be a more standard format like MM/DD/YYYY so that users have a clear idea on how to enter a date filter.

### Future Enhancements
To further develop this webpage, I suggest standardizing the format of the values in the table, and allowing the search parameters to be non-case sensitive for easier use by the end user.
