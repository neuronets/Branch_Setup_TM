# Branch Setup and Issue Parser

This is a composite action used in the workflow of updating a model. This process is evident in Nobrainer's Trained-Models repository action course.

In addition, this composite action is used to compress the amount of code in a single workflow, and avoid duplication with the first workflow in Trained-models: Add a new model.

In summary, this action will:

Create a new branch for the issue linked.
Parse the issue form's information/text fields.
Save the parsed information to output variables to be used within the context of the calling workflow.
