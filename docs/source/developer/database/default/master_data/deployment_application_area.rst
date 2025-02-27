:html_theme.sidebar_secondary.remove:

deployment_application_area
====

Download the definition as a CSV file: :download:`csv <deployment_application_area.csv>`.

.. csv-table:: Definition of the *deployment_application_area* table.
   :header: "Property","Kind","References","Requirement","Description"

   ".. _id:

   id","str",,"Required","Primary key for this record."
   ".. _deployment:

   deployment","str","`master_data.deployment.id <../master_data/deployment.html#id>`_","Required","The deployment this record belongs to."
   ".. _application_area:

   application_area","str","`reference_data.application_area.id <../reference_data/application_area.html#id>`_","Required","The application area this record belongs to."
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

