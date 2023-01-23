# Our-History-Global-Queer-Rights-Through-a-Historical-Colonial-Lens

I am interested in the comparative rights of queer people globally. Like in the US, British colonialism has cast a long  shadow of colonial violence on queerness across the  world. 

To understand the history of global homophobia and transphobia, I created a unique dataset of historical buggery law/penal code (laws against sexual acts that are determined to be “unnatural or immoral”) introductions for 55 Commonwealth countries as well as the dates that those Commonwealth countries were formally colonized.

To download all files, click the <i>Clone or download</i> drop down arrow and select "Download ZIP". This will download all the data sets used. Another option is to click on the file that you are interested in and click the "Raw" button which will open the file the browser. From here, the URL link can be used in R with the `read.csv()` function -- `read.csv("https://raw.githubusercontent.com/.../")`.


<b>Datasets</b>

The <b>buggery.csv</b> file is [original research with incomplete notes and citations, year of buggery intro (first recorded year of any sodomy/buggery law in country); year colonized (year of official colonial government established);notes (anything notable about each individual countries' history); buggery citations ( citation for introduction of laws); year colonized citations (citations for year colonized), (Citations are incomplete--I am hoping to continue to add citations as I want this dataset to be an accurate and robust source about historical queer oppression.]

The <b>final.csv</b> file is [cleaned up csv file from original research with Brunei removed, formatted for R, country names; country region; buggeryYear (first recorded year of any sodomy/buggery law in country); colonizationYear(year of official colonial government established); gayScore (Franklin & Marshall Global Barometer of Gay Rights (GBGR®)); transScore (Global Barometer of Transgender Rights (GBTR™); https://www.fandmglobalbarometers.org/results/ ( dates for buggeryYear and colonizationYear are subject to change as I find more sources.]
