# Opinion Questions Machine Reading Comprehension Evaluation
Opinion Questions Machine Reading Comprehension is a task of AI Challenger 全球AI挑战赛。This python script is used for calculating the accuracy of the test result, based on your submited file and the reference file containing ground truth.  (This script is the lastest and robust version. )
# Usage
```
python oqmrc2018_eval.py --submit SUBMIT_FILEPATH --ref REF_FILEPATH
```
A test case is provided, submited file is pred.txt, reference file is ans.txt, test it by:
```
python oqmrc2018_eval.py --submit ./pred.txt --ref ./ans.txt
```
The accuracy of the submited result, error message and warning message will be printed.    
