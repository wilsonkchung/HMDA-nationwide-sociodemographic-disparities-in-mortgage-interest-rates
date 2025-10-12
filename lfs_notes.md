# To use GitHub Large File Storage (LFS):

MacOS:

brew install git-lfs

## initiate:

git lfs install

## track:

git lfs track "*.zip"

after running track command, this line will appear in .gitattributes "df_trimmed.csv.zip filter=lfs diff=lfs merge=lfs -text"

## add, commit, push

git add .gitattributes

git commit -m ""

git push