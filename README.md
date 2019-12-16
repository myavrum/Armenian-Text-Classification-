# Facebook's Comment Classification Dataset (in Armenian)

### Multi-label Classification

Version 0.9, Released 13/12/2019


## ORIGIN

The dataset is a collection of about 1k Facebook posts and comments in Armenian. Each post has at least 1 comment. The data have been gathered from 4 Facebook sources, manually, in more than 6 months of activity (May-Oct-2019). The data were annotated by using the doccano open source text annotation tool (for more information, please refer to the link https://github.com/doccano/doccano). The dataset is provided the academic community for research purposes in data mining (clustering, classification, etc.), information retrieval (ranking, search, etc.), xml, data compression, data streaming, and any other non-commercial activity.

The FB's comment classification dataset is constructed by Marat Yavrumyan (myavrum@ysu.am).


## DESCRIPTION

The Facebook's comment classification dataset is constructed by choosing 4 largest topic domains (labor and social affairs, health, education and science) from the original corpus. The topic domain of labor and social affairs contains 231 training samples, health - 391, education and science - 376. The total number of training samples is 998. There are no testing samples.

The file classes.txt contains a list of classes corresponding to each label.

The files MLSA.json, MoH.json and MoES.json contain all training samples as comma-separated values. There are 5 columns in them, corresponding to text id, text, label index (43 to 86), annotator index, metainformation and annotation approver. All columns are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). Labels are escaped by curly brackets in frame of square brackets. New lines are escaped by a backslash followed with an "n" character, that is "\n". There are no new lines in dataset.


## PAGES SCRAPED

* 'Facebook_Ազատություն ռադիոկայան',
* 'Facebook_ՀՀ աշխատանքի և սոցիալական հարցերի նախարարություն',
* 'Facebook_ՀՀ առողջապահության նախարարություն',
* 'Facebook_ՀՀ կրթության, գիտության, մշակույթի և սպորտի նախարարություն'.
