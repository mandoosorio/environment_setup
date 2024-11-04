1. Download vs code
  -"open in browser" extension (TechER)
  -"indent one space" extension (Alexander)
  -"HTML boilerplate" extension (sidthesloth)
  -"Live Preview" extension (Microsoft)
  -"Output Colorizer" extension (IBM)
  -"Rainbow Brackets" extension (2gua)
2. Download git (https://git-scm.com/downloads)
   - Download BitBucket (https://www.atlassian.com/software/bitbucket/download)
4. Download nodejs
5. Login to Github
6. create ssh key:
  (Windows)
  - open bash
  - ```ls -al ~/.ssh``` (to check existing keys)
  - ```ssh-keygen -t rsa -b 4096 -C "email"```
  - ```eval "$(ssh-agent -s)"```
  - ```ssh-add ~/.ssh/id_rsa```
  - ```clip < ~/.ssh/id_rsa.pub (or cat instead of clip)```
  - ```ssh -T git@github.com```

  (Mac)
  - same steps, except copy command is ```pbcopy < ~/.ssh/id_rsa.pub```
  - may have to create the ssh folder: ```mkdir -p ~/.ssh```
  - if there is an error with hosts, go into ssh folder and delete the config file ```cd ~/.ssh```
6. setup git for github:
  - ```git config --global user.name "username"```
  - ```git config --global user.email "email"```
