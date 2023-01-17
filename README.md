# cnndiabeticretinopathylite

## to download dataset

**form Windows**

```
Go to your kaggle profile, and select the "Accounts" tab.

Scroll down and click on "Create API token" button.

(A json file will be downloaded called kaggle.json)


run this command from windows powershell as administartor :

pip install tqdm  text-unidecode python-slugify  slugify kaggle

add folder with windows explorer with ".kaggle" in user folder and copy kaggle.json to it

Copy the downloaded "kaggle.json" to your "C:\Users\[yourUser]\.kaggle\kaggle.json"

The library can now detect your user authentication from the json file.

Run this command from windows powershell:


kaggle datasets download -d assiri/cnndiabeticretinopathyliteimages

```

**form Mac**

```
Go to your kaggle profile, and select the "Accounts" tab.

Scroll down and click on "Create API token" button.

(A json file will be downloaded called kaggle.json)
from terminal run:
cd ~/
mkdir ~/.kaggle
then Copy the downloaded "kaggle.json" to  "~/.kaggle\kaggle.json"
kaggle datasets download -d assiri/cnndiabeticretinopathyliteimages
```
