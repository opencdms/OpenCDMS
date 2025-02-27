:html_theme.sidebar_secondary.remove:

deployment_log
====

Download the definition as a CSV file: :download:`csv <deployment_log.csv>`.

.. csv-table:: Definition of the *deployment_log* table.
   :header: "Property","Kind","References","Requirement","Description"

   ".. _id:

   id","str",,"Required","ID / primary key."
   ".. _deployment:

   deployment","str","`master_data.deployment.id <../master_data/deployment.html#id>`_","Required","The deployment to which this record applies."
   ".. _author:

   author","str",,"Required","Author of the log entry."
   ".. _datetime:

   datetime","datetime",,"Required","Date and time of the event being logged."
   ".. _description:

   description","str",,"Required","Description of of the event being logged."
   ".. _links:

   links","dict",,"Required","Links to further documentation of the logged event."
   ".. _version:

   _version","int",,"Required","Version number of this record."
   ".. _change_date:

   _change_date","datetime",,"Required","Date this record was changed."
   ".. _user:

   _user","str","`admin.user.id <../admin/user.html#id>`_","Required","Which user/agent last modified this record."
   ".. _status:

   _status","str","`reference_data.status.id <../reference_data/status.html#id>`_","Required","Whether this is the latest version or an archived version of the record."
   ".. _comments:

   _comments","str",,"Required","Free text comments on this record, for example description of changes made etc."

