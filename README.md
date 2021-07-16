**False Connector for Document Tracking**

Use Cases

* Applying document tracking anywhere in the process.  This is especially useful if all the operations are batch.  This connector could be put in line at some point where the documents are split, recording the record id's per document in process reporting and better enabling searching by tracked fields.
* Ability to retrieve documents anywhere in the process from the documents API.  This could be particularly useful for test harness processes and test assertion.
* Ability to record un-truncated error results  to process reporting or recording documents at specific steps for troubleshooting.  Notify and exception shapes would logically be used, but are truncated at 10K characters.  The return documents shape can accomplish this, but is only useful at the top level process and not usable in webservice processes since this shape is functional.