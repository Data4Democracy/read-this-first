## Best Practices for D4D datasets on data.world
Here’s some guidelines and FAQs for how Data for Democracy members can use data.world  

### What is data.world?   
data.world is a social network for data people; users can discover and share cool data, connect with interesting people, and work together to solve problems faster. 

### What should D4D use data.world for?   
data.world is a repository for D4D datasets and a workspace for collaboration on D4D data projects. Here are some of the distinct advantages to storing data in data.world vs. GitHub or other repositories:
* Great presentation of data via file previews and data visualizations
* Allows for live querying and joining datasets via a query tool, saved queries and API
* Live free-form discussions around data
* Data-specific search
* Ability to join to external semantic data sources such as dbpedia and wikidata
* Editable column and file meta descriptions
* Easily accessible/viewable for others (though you have the option to keep your dataset private vs. open)

### What if I’m already storing my data in another repository?  
If your data is already in GitHub or another cloud storage repository (S3, Dropbox, Drive, etc), you can convienently mirror your data into data.world via their sync API (requires some programming, reach out in #tools-support for help on this). data.world is imminently releasing RESTful APIs for basic CRUD operations inside datasets that will further ease the workflow of updating data in data.world.   

More info here: [data.world API documentation](https://docs.data.world/documentation/api/)   

### How do I get started on data.world?
1. Sign up for an account on [data.world](https://data.world), and let @jonathon or @sharon know so they can add you as a contributor. This will grant you upload privileges to the current D4D projects (we'll add more later!)
2. When you have a dataset you'd like to share publicly or collaborate on with other volunteers, upload it through the data.world UI.
3. If you own datasets in data.world that are not in [data.world/Data4Democracy](https://data.world/data4democracy) for whatever reason, but you'd like to connect them to a D4D project you can:  
    * Utilize Tags: Add the `d4d` tag and if data is related to a specific project, we encourage you to add the tag(s) that corresponds to the project, e.g. `election transparency`, `house expenditures`, `propublica`, etc.
    * Add D4D as Contributor: Add D4D as a contributor to keep data under the same umbrella
    * For datasets that you do not own but are used in your project, link to them in your summary or request to be a contributor and add tags
4. You can explore the data on data.world and can use their API to send SQL queries and get CSVs (and, subsequently, dataframes!) back! Coming very soon - the ability to upload data via the API as well!
5. Now all the datasets for a project can live in one place. You can comment on them, annotate them, access them programmatically. Boom!
6. As you may have noticed, lots of the data.world team are actually in the community volunteering on various projects. If you have technical questions and aren't sure who to get in touch with, join the `#tools-support` channel and ask the room.

### How should we organize files within the project-specific datasets (folders vs. tags, etc.)
Right now files are organized alphabetically within datasets specific to each D4D channel/workgroup. While data.world will be adding folders or tagging in the near future, currently most datasets only have a handful of files. Therefore, our current best practice is to prefix the filenames to logically group or order them.

_Example:_ Filetype_01_name.pdf

### What file types can I upload?
The following file extensions are enhanced during import, which means they can be queried and previewed (tabular files only) within data.world:
* Tabular files: csv, tsv, xls, xlsx
* Raw triples / RDF files: rdf, rdfs, owl, jsonld, nt, ttl, n3

_The following file extensions can be previewed within data.world:_
* jpg, jpeg, png, gif, svg, pdf, md, txt, ipynb (version 4 and higher), js, r, py, json, as, apl, bash, bas, bat, c, cpp, cs, css, d, dart, diff, go, html, ini, java, julia, kt, lua, matlab, nasm, ml, perl, php, ps1, rb, scala, sql, tcl, ts, vim, yaml, xml, asp, jade, tex, less, sass, scss, Dockerfile

_For the following formats, we will attempt to extract and store the contained files (up to 50), handling each file based on its extension:_
* Archive formats: zip, tar
* Compression formats: tbz2, tbz, bz2, tgz, gz, -gz, z, -z

_All other file types can be uploaded and downloaded as long as they are within the supported size limits._

### What are the size restrictions for data.world?

_Individual File Upload Limitations:_
The maximum file size you can upload to data.world is currently 100MB. If you have a file that is larger than that, try compressing the file to get it under the 100MB limit and if that doesn't work, please contact us via a new help ticket. If your file is significantly larger than the maximum, you'll need to split it into multiple files in order to upload it.

_Inference & Preview Limitations:_
Non-tabular files that are previewable only display a preview if less than 40k.

For xls / xlsx, the file must be less than 10MB uncompressed for us to enhance the data so it can be queried and previewed within data.world. 

For other tabular files, if the generated triples files are over 5GB, the files will only be downloadable. This is determined behind the scenes on the platform, so if it's a larger tabular file that doesn't display a preview to the data, it means it was too large for us to handle.

_Dataset Limitations:_
There is a maximum of 100 individual files per dataset currently.   


### Any other resources I should know about?     
[data.world API documentation](https://docs.data.world/documentation/api/)    
[data.world knowledge base & support site](https://help.data.world/support/home)    
[data.world tutorials](https://docs.data.world/)    
[data.world file upload error messages](https://help.data.world/support/solutions/articles/14000049447-file-upload-error-messages)
