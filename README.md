# Static Website for the 2022 Swiss Summit

A [Lektor](https://www.getlektor.com/) powered project.

To run the website:

* Clone the repository
* Install requirements with `make install`
* Run Lektor server with `make serve`

After that the website should be available on port 5000.

## How to add a talk recording

- Go to http://localhost:5000/admin/root:talk-recordings/edit
- Click "Add Page"
- Choose the "Recording" model
- Set the "Title" field to the talk title
- Click "Add Child Page"
- Fill in the data and save
- Click "Add Attachment"
- Upload PDF file with slides
- Click on the attachment in the left navigation
- Change the attachment type to "Slides"

Note: The playlist URLs are stored in `databags/playlists.json`.

## Develop with Gitpod
<a href="https://gitpod.io/#https://github.com/turbotimon/web-sps20">
  <img
    src="https://img.shields.io/badge/Contribute%20with-Gitpod-908a85?logo=gitpod"
    alt="Contribute with Gitpod"
  />
</a>

---

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/turbotimon/web-sps20)