# UFOs

## Overveiw: 
##### The purpose of theis assignment was to integrate JavaScript to manipulate HTML code to build a working website that could hold data tables. This website consists of information surrounding UFO sightings. It allows one to filter these sighting by date, city, state, country, and shape. This will filter this information and provide a table that include the information that was entered along with the duration of the sighting and the a comment section to further descibe the UFO sighting in detail.
---
## Results: 

##### The web page has been organized to present 5 different filter options that will organize the information in a table-like formation. If you notice in the image the filtered textbox has the Date set to 1/1/2010 and the City set to "el cajon". The filter takes what was inputed and excutes it in the table for those matching items. 
![image](https://user-images.githubusercontent.com/105329532/191847281-06908ea0-eff8-491a-8602-7f5eb5bfad7f.png)
![image](https://user-images.githubusercontent.com/105329532/191849621-4c3a262e-c784-4453-b444-808633e23307.png)

The HTML code shown below largely structured the table executed within the browser webpage:
This created the 5 filters used to extract information from the table set.

![image](https://user-images.githubusercontent.com/105329532/191850525-e156e422-6716-4281-802a-7f1a4b760433.png)

An important line of code that is the key to the filter being usable is shown below. Without this you will have the structure and table of data, but it will not register or save the filters you want to execute to the table. In other words, nothing will appear in the table. 
![image](https://user-images.githubusercontent.com/105329532/191850957-051a0058-a7f8-4078-8bff-475268af2fa9.png)

This is the link to the website : http://127.0.0.1:5500/UFOs/index.html

---
## Summary:
The drawback of this webpage is that it does not provide a range or suggested items to input so you could reppeatedly input a date that is not in the dataset.
* I would reccomend still allowing item to populate even if it is not an exact match. For example if I entered the 1/1/2022 nothing would populate, but it would be beneficial if the closest dat to that record did come up. 
#### Room for Improvement...
* It would reduce the time it takes to search and give you an idea of what the dataset provides rather than presenting nothing which I think is helpful as a web user with no knowledge on the dataset used for this. 
* I also think maybe providing a message that what you have enetered is out of the dataset bounds would be beneficial so that it is more user friendly in understanding the datasets capabillities. 
