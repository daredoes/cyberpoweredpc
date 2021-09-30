# Cyber-Powered PC
#### A cyber-powered PC builder for cyberpowerpc.com

## Install
```bash
pip3 install cyberpoweredpc
```
<img width="575" alt="Screen Shot 2021-09-30 at 11 19 45 AM" src="https://user-images.githubusercontent.com/6538753/135533405-55b1c1a7-a633-4bc8-b5c9-cf2f7ae3c8dc.png">


## Run
```bash
# This will show the available commands
python3 -m cyberpoweredpc
```

<img width="598" alt="Screen Shot 2021-09-30 at 11 33 05 AM" src="https://user-images.githubusercontent.com/6538753/135533429-a93c69ca-75ef-48c4-b0a7-0f6b7df2ec63.png">

### Create

We run this command to begin build our ideal PC. Ideal meaning it has the right parts, not necessarily the right price!

1. A Chrome Browser will open up to cyberpowerpc.com where we will select our starting PC. The most important question here is *AMD* or *INTEL*?
<img width="1200" alt="Screen Shot 2021-09-30 at 11 33 29 AM" src="https://user-images.githubusercontent.com/6538753/135533538-c6a45b5a-ddf3-444d-94e1-2f92aa65a9ba.png">

2. We click "customize" on the desired base PC.
<img width="331" alt="Screen Shot 2021-09-30 at 11 33 42 AM" src="https://user-images.githubusercontent.com/6538753/135533659-f34c525c-625b-4036-84b1-0d5885aebf6d.png">

3. The desired base PC page will load. Once loaded, we will be guided through each section of the customization form. Some sections include instructions/tips!
<img width="1202" alt="Screen Shot 2021-09-30 at 11 33 53 AM" src="https://user-images.githubusercontent.com/6538753/135533815-9e33f14a-75ed-4e7e-95dc-3afa3ef1239c.png">

4. When we finish picking our part(s) for a section, we click some manually-inserted "Finish" buttons.
<img width="521" alt="Screen Shot 2021-09-30 at 11 34 07 AM" src="https://user-images.githubusercontent.com/6538753/135533899-121fd4e2-b582-423a-80ae-dc2daf7a8c67.png">

5. In some sections, we'll want to mark a part as *required*. If we find a required part is *missing* when automatically trying to build a PC, we will discard that PC as an option and add it to a list of *Bad PCs* to save us time in future runs of the program.
<img width="466" alt="Screen Shot 2021-09-30 at 11 34 40 AM" src="https://user-images.githubusercontent.com/6538753/135534044-0b4306db-6869-4e97-b54a-1ee8a6e35485.png">

We recommend setting at least the CPU and the graphics card as requirements. If the CPU isn't set as required the program won't be able to pick our motherboard, and we'll get messy results!
<img width="908" alt="Screen Shot 2021-09-30 at 11 34 48 AM" src="https://user-images.githubusercontent.com/6538753/135534207-7be0e677-2798-4996-8f0c-0bfec13f422f.png">

6. When we've completed the final section of the customization form, the program will close. These results will be saved to our results folder.

### Find

We run this command to search for our ideal PC. Ideal meaning it has our preferred parts, and the right price!

1. A Chrome Browser will open up to cyberpowerpc.com, if we do not have a list of preferred parts the program will ask to put one together.
2. The program collects all available PC builds on the page. This list of URLs will be compared against a list of saved *BAD* URLs that we know are incompatible with our preferred/required parts. The program will then begin automatically building the ideal PC on each possible web page, storing the results as it goes.
3. When the program finishes it will save an updated list of *bad* URLs, as well as a sorted JSON file with our results. The first entry should be the cheapest entry. Every entry in the file should have the same build, if not a very similar one.
<img width="924" alt="Screen Shot 2021-09-30 at 11 53 02 AM" src="https://user-images.githubusercontent.com/6538753/135535135-23188c8c-6263-45a7-9e9c-19236e5d657b.png">

4. Go to the included link for the top result to reach cyberpowerpc's customization form, select your preferred parts manually, and confirm the price is right where we expect it to be!
5. If the PC has the parts you want and the price is where you'd like it, proceed to checkout to get your ideal PC! If you think the price might change based on the economy/freebies/deals close the window and wait to run the program again another day!

# I hope this helps you find your perfect PC! Let me know if it does!
#### Computers purchased so far using this program that I am aware of: 2
