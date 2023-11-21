# share-folder-to-My-drive-google-drive
# Copy Data from Shared Folder to Google Drive using Google Colab

# Step 1: Mount Google Drive
from google.colab import drive
drive.mount('/gdrive')

# Step 2: Set Working Directory
%cd /gdrive/MyDrive/<path to the link added in step 5>

# Step 3: Check Current Path
!pwd

# Step 4: Copy Data
!cp -r 'above-copy-path/.' '/gdrive/My Drive/destination-path'
