# suc-ragit-rag-rust















it run in win 10 with poershelll

and run in wsl in win10

powersshel

C:\Users\TARGET STORE\Desktop\2\ragitمتغيرات بيئة
يحتوى على
ragit-windows11-x64.exe

$env:GROQ_API_KEY = "مفتاح_API_الخاص_بك_هنا"

ragit-windows11-x64.exe init

ragit-windows11-x64.exe add 1.txt

ragit-windows11-x64.exe build

ragit-windows11-x64.exe ls-chunks

ragit-windows11-x64.exe query "What is the 1.txt content?"

..................................

PS C:\Users\TARGET STORE\Desktop\2\ragit\w> ragit-windows11-x64.exe query "What is the 1.txt content?"
The 1.txt content appears to be a comprehensive text about climate change, covering topics such as:

Introduction to climate change: definition, historical context, and modern observations.
Causes of climate change: greenhouse gases, fossil fuels, deforestation, and agriculture.
Effects of climate change: rising temperatures, heatwaves, changing seasons, melting ice, and rising sea levels.
Solutions to climate change: renewable energy, energy storage, carbon capture and utilization, sustainable transportation, and sustainable agriculture.
Global and local climate action: international collaboration, national strategies, and individual actions.
The text is well-structured and divided into chapters, making it easy to follow and understand. It provides a broad overview of the topic, covering both the science and the solutions to climate change.

---- sources ----
1st chunk of 1.txt (da3ccd63)
7th chunk of 1.txt (6f196f0d)
2nd chunk of 1.txt (b37d35b7)
PS C:\Users\TARGET STORE\Desktop\2\ragit\w>

........................

wsl

downlooaad
https://github.com/baehyunsol/ragit/releases/download/v0.3.5/ragit-linux-x64

wget https://github.com/baehyunsol/ragit/releases/download/v0.3.5/ragit-linux-x64
chmod +x ragit-linux-x64
sudo mv ragit-linux-x64 /usr/local/bin/ragit
ragit --version

ragit help

export GROQ_API_KEY="gsk_..."
ragit init

ragi add 1.txt
ragi build

ragit query "What is the 1.txt content?"

..............................................

m@DESKTOP-MUB16F8:~/ragit/k$ ragit query "What's in the file?"
The file contains information about climate change. The first chapter includes an introduction to climate change, discusses long-term changes in global climate, and addresses the historical context of climate change. It notes that these changes have a long history dating back 650,000 years, with seven cycles of glacial advance and retreat, culminating in the beginning of the modern era through the end of the last ice age. The chapter also covers recent observations indicating a rapid increase in global temperatures, sea levels, and extreme weather events, primarily due to climate change, particularly through the emission of greenhouse gases.

Chapter 2 addresses the causes of climate change, stating that greenhouse gases are the primary cause of modern climate change. These gases trap heat from the sun, creating what is known as the greenhouse effect. It also notes that human activities have greatly accelerated this process, leading to an increase in temperatures. Chapter 2 also covers the use of fossil fuels as a cause of climate change. Coal, petroleum, and natural gas are used to generate energy, leading to increased carbon dioxide emissions. These benefits include methane emissions, a potent greenhouse gas, resulting from the extraction, processing, and consumption of these resources.

The file also includes information on deforestation, as forests play a role in absorbing carbon dioxide. When these forests are destroyed, the stored carbon is released back into the atmosphere, increasing the greenhouse effect.

1st chunk of 1.txt (db4eaf28)

.................................................

