--- 
### IMAGE ANALYSIS AND CLASSIFER

#### Summary
Input an image, run either both analysis and classification, or analysis, or just classification and all its information will be outputted via a word doc file.

---
#### API installation
```bash
Run these commands:

pip install ultralytics
pip install deepface
pip install python-docx
```

---
#### Command line guide
```bash
Example runs for each mode 

Format : python main.py --mode [choice] --img [image Path] --classification [optional classifier model] --identification [optional identifier model]

There are tonnes of other available models check out the ultralytics api page, by default we are using their best ones available. You are free to train your own and use them.

python main.py --mode analysis --img Images/1.jpg
python main.py --mode both --img Images/1.jpg
python main.py --mode classification --img Images/1.jpg

python main.py --mode classification --img Images/1.jpg --classification customC.pt --identification customI.pt
```


---

#### General Information and Usage:
- ANALYSIS ONLY WORKS FOR CLEAR 1 ON 1 FACIAL IMAGES LIKE IN THE EXAMPLE

- On default models available from ultralytics will contain some descrepancies project is limited by this performance as I lack the tech to train my own models.

---

#### Example Output Document

[Example document link](Example_report_output/detections.docx)

--- 