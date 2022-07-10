# Quiz-Gather-Import-c.12-l.1-
online-job-postings.csv [91.5 MB-big]

Gather

import pandas as pd
import zipfile

# Extract all contents from zip file
with zipfile.ZipFile('armenian-online-job-postings.zip', 'r') as myzip:
    myzip.extractall()

# Read CSV (comma-separated) file into DataFrame
df = pd.read_csv('online-job-postings.csv')
