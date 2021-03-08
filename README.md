# documents

It is a json file containing a list of dictionary.

After loading in python this way:

import codecs
import json
document_list = json.loads(codecs.open("document_release.json", 'r', 'utf-8').read())

document_list is a list whose element is dictionary.
Each dictionary contains four keys: document_id, topic, title and  content
document_id is an unique id for this document.
topic represents which topic this document comes from


Altogether there are 6500 documents.
