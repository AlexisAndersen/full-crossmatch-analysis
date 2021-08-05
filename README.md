# full-crossmatch-analysis
Collection of different analysis methods for Crossmatch results

When provided a survey name (snls, ztf ...) and arcsecond range, the function will return a csv of the selected crossmatch results, histogram of the distrubution over the arcsecond range, and all of the Legacy Survey Cutouts for the image. Will be expanded so that the csv file includes a link to the DESI Spectra of the host galaxy. 

Requires that xmatch_all.csv is downloaded in the home directory. Check that SNLS is not capitalized in the csv (if it is, contact Alexis for an adjusted list).

Reading in the csv files requires a unique filepath. Currently there is an input function that allows Ruby, Autumn, Caitlin, and Alexis to input their names so that the function does not have be adjust for each, but outside of that it will need to be updated. Possibly, home directory file path could be an input so that anyone can use it.
