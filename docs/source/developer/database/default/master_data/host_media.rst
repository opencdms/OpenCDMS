:html_theme.sidebar_secondary.remove:

host_media
====

Download the definition as a CSV file: :download:`csv <host_media.csv>`.

.. csv-table:: Definition of the *host_media* table.
   :header: "Property","Kind","References","Requirement","Description"

   ".. _id:

   id","str",,"Required","Primary key for this record."
   ".. _host:

   host","str","`master_data.host.id <../master_data/host.html#id>`_","Optional","The host to which this media belongs."
   ".. _media:

   media","str","`master_data.media.id <../master_data/media.html#id>`_","Optional","The associated media."
   ".. _valid_from:

   valid_from","datetime",,"Optional","Date from which this record is valid."
   ".. _valid_to:

   valid_to","datetime",,"Optional","Date from which this record is no longer valid."
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

