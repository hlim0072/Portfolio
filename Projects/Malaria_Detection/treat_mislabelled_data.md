### commands used in cmd to filter mislabelled data from cell images dataset

#### 1. 
FOR /F "delims=" %N in (C:\Users\Administrator\Desktop\cfilenames0.txt) do COPY "%N" C:\Users\Administrator\Desktop\Uninfected
(open cmd anywhere is ok)
(repeat for infected i.e. 1)

#### 2.
for /f %i in (C:\Users\Administrator\Desktop\cfilenames0.txt) do del %i
(open cmd in original folder that wanna delete imgs from)
(repeat for infected i.e. 1)
