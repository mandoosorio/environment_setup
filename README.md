1. Download vs code
  -"open in browser" extension (TechER)
  -"indent one space" extension (Alexander)
  -"HTML boilerplate" extension (sidthesloth)
  -"Live Preview" extension (Microsoft)
  -"Output Colorizer" extension (IBM)
  -"Rainbow Brackets" extension (2gua)
2. Download git
3. Download nodejs
4. Login to Github
5. create ssh key:
  (Windows)
  - open bash
  - ls -al ~/.ssh (to check existing keys)
  - ssh-keygen -t rsa -b 4096 -C "email"
  - eval "$(ssh-agent -s)"
  - ssh-add ~/.ssh/id_rsa
  - clip < ~/.ssh/id_rsa.pub
  - ssh -T git@github.com
  (Mac)
6. setup git for github:
  - git config --global user.name "username"
  - git config --global user.email "email"
