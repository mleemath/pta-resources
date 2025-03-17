# PTA Resources

## FOR USERS  
This is a repository for resources for parents to download worksheets for their children.  

Visit the website: [PTA Resources](https://mleemath.github.io/pta-resources/)  

Click on any card to download the corresponding worksheet.

---

## FOR ADMIN  
### Uploading a File  
1. Navigate to **`assets -> worksheets`** in the repository.  
2. Click **"Add file"** on the right to upload a new worksheet.  
3. Once uploaded, the file will be stored at:  
assets/worksheets/FILENAME.ext
- `.ext` represents the file type (`jpg`, `pdf`, `png`, etc.).
- The file is now in the system and can be used on the website.

---

### Updating the Website  
To modify the website content, edit **`index.html`**.  

#### Adding or Updating a Worksheet Card  
Each worksheet is displayed as a **clickable card** in `index.html`:
```html
<a href="assets/worksheets/test-file.jpg" download class="file-card" style="background-image: url('assets/worksheets/test-file.jpg');">
 <span class="download-text">Download File</span>
</a>
```
- href="assets/worksheets/test-file.jpg" → Change this to update the file being downloaded.
- background-image: url('assets/worksheets/test-file.jpg'); → Change this to update the preview image displayed on the card.
