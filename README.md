Docker image for lab exercises with open data from the ATLAS experiment, using pyROOT in jupyter notebooks. Different branches check out different repos of actual exercises. Each branch is built into an image with a tag named as the branch, usually the course code. So, for course SH1015 you can run the lab like this:

`docker run -p 3000:8080 cohm/opendatalab:SH1015`

and then access by going to localhost:3000 in your browser.
