# To use GitHub Large File Storage (LFS):

MacOS:

brew install git-lfs

- initiate: git lfs install

- track: git lfs track "*.zip"

- after running track command, this line will appear in .gitattributes "df_trimmed.csv.zip filter=lfs diff=lfs merge=lfs -text"
    - git add .gitattributes, commit, push

- Once .gitattributes is pushed, then push the large file itself