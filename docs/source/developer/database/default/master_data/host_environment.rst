:html_theme.sidebar_secondary.remove:

host_environment
====

Download the definition as a CSV file: :download:`csv <host_environment.csv>`.

.. csv-table:: Definition of the *host_environment* table.
   :header: "Property","Kind","References","Requirement","Description"

   ".. _id:

   id","str",,"Required","Primary key for this record."
   ".. _host:

   host","str","`master_data.host.id <../master_data/host.html#id>`_","Required","Host associated with this record."
   ".. _climate_zone:

   climate_zone","str","`reference_data.climate_zone.id <../reference_data/climate_zone.html#id>`_","Optional","Climate zone that the associated host is located in."
   ".. _surface_cover:

   surface_cover","str","`reference_data.surface_cover.id <../reference_data/surface_cover.html#id>`_","Optional","Type of surface cover."
   ".. _surface_roughness:

   surface_roughness","str","`reference_data.surface_roughness.id <../reference_data/surface_roughness.html#id>`_","Optional","Typical surface roughness of the site surrounding the host."
   ".. _altitude_or_depth:

   altitude_or_depth","str","`reference_data.altitude.id <../reference_data/altitude.html#id>`_","Optional","The altitude/depth with respect to mean sea level (enumerated)."
   ".. _local_topography:

   local_topography","str","`reference_data.local_topography.id <../reference_data/local_topography.html#id>`_","Optional","The local topography."
   ".. _relative_elevation:

   relative_elevation","str","`reference_data.relative_elevation.id <../reference_data/relative_elevation.html#id>`_","Optional","The relative elevation."
   ".. _topographic_context:

   topographic_context","str","`reference_data.topographic_context.id <../reference_data/topographic_context.html#id>`_","Optional","The topographic context."
   ".. _valid_from:

   valid_from","datetime",,"Optional","Date the this record is valid from"
   ".. _valid_to:

   valid_to","datetime",,"Optional","date that this record is valid to"
   ".. _version:

   _version","int",,"Required","Version number of this record"
   ".. _change_date:

   _change_date","datetime",,"Required","Date this record was changed"
   ".. _user:

   _user","str","`admin.user.id <../admin/user.html#id>`_","Required","Which user/agent last modified this record"
   ".. _status:

   _status","str","`reference_data.status.id <../reference_data/status.html#id>`_","Required","Whether this is the latest version or an archived version of the record"
   ".. _comments:

   _comments","str",,"Required","Free text comments on this record, for example description of changes made etc"

