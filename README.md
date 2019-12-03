Docker image for lab exercises with open data from the ATLAS experiment, using pyROOT in jupyter notebooks. Different branches check out different repos of actual exercises. Each branch is built into an image with a tag named as the branch, so for the lab for the course SH2103 Subatomic Physics, run with like this:

`docker run -p 3000:8080 kthatlas/opendatalab:SH2103`

and then access by going to `localhost:3000` in your browser.
