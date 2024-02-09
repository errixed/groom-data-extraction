<div align="center">

<img src="https://skillicons.dev/icons?i=js" />
<img
src="https://www.gstatic.com/images/branding/product/2x/sheets_96dp.png"
width="60px"/>
<img
src="https://www.gstatic.com/images/branding/product/2x/classroom_96dp.png"
width="60px"/>
<img
src="https://www.gstatic.com/images/branding/product/2x/gmail_96dp.png"
width="60px"/>

# gcroom-data-extraction
This code is a extenstion for a Google Sheets. It will help you to extract the students' assignments status from Google Classrooms into Sheets.
This code will help you to schedule sending email to the student who didn't submit their assignment.
Also you can schedule data extraction time daily or weakly to get the updates.

<br/>

![GitHub followers](https://img.shields.io/github/followers/errixed)
![GitHub forks](https://img.shields.io/github/forks/errixed/groom-data-extraction)
![GitHub watchers](https://img.shields.io/github/watchers/errixed/groom-data-extraction)
![GitHub Repo stars](https://img.shields.io/github/stars/errixed/groom-data-extraction)

</div>


## Setup
1. Go to `Google Drive`
2. Create a `new Google Sheets`
3. In the `Extensions` tab, select `Apps Script` (Apps Script will be opened)
4. In Apps Script, go to `Settings` and check the `Show "appsscript.json" manifest file in editor` option
5. Copy and paste codes in `appsscript.json` from this repo to apps script
6. Copy and paste codes in `Code.gs` from this repo to apps script
7. Replace `SELECTED_COURSE_ID` on line 27 with `your course ID`

## On Run
 - Run `courseData` function to get course IDs that you have access with
 - Run `assignmentSubmissionState` function to get students data (names, emails, submission statuses)
