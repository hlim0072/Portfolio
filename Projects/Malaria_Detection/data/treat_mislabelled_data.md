### commands used in cmd to filter mislabelled data from cell images dataset

pre-step: export filenames into a .txt file from the modified dataset (image folder) since it only contains correctly labelled data. then we can filter the original dataset based off these correct filenames 

#### 1. to obtain folder with only correctly labelled images
FOR /F "delims=" %N in (C:\Users\Administrator\Desktop\cfilenames0.txt) do COPY "%N" C:\Users\Administrator\Desktop\Uninfected
<br>(open cmd anywhere is ok)
<br>(repeat for infected i.e. 1)

#### 2. to obtain folder with just mislabelled images
for /f %i in (C:\Users\Administrator\Desktop\cfilenames0.txt) do del %i
<br>(open cmd in original folder that wanna delete imgs from)
<br>(repeat for infected i.e. 1)
