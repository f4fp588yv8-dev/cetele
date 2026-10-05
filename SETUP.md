# Setup (about 10 minutes)

## 1. Create the shared sheet
1. Go to sheets.google.com and create a blank spreadsheet. Name it "Kuran Cevsen".
2. Open Extensions > Apps Script.
3. Delete the sample code, paste in everything from Code.gs, and click Save.

## 2. Publish it as a web app
1. Click Deploy > New deployment > the gear icon > Web app.
2. Execute as: Me.
3. Who has access: Anyone.
4. Click Deploy and approve the permissions (Google may show an "unsafe app" warning; choose Advanced > Go to project).
5. Copy the Web app URL. It starts with https://script.google.com/macros/s/ and ends with /exec.

## 3. Connect the page
1. Open index.html in a text editor.
2. Replace PASTE_YOUR_APPS_SCRIPT_URL_HERE with the URL you copied.
3. Upload index.html to your website (it is one file; no other files needed).

## 4. Test
Open your page in two browsers, take a cuz in one, and wait up to 15 seconds: the name appears in the other. You can also see and edit all sign-ups in the "claims" tab of your sheet.

If you change Code.gs later, use Deploy > Manage deployments > Edit > New version.
