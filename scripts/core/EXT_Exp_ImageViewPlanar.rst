<%
import re
from templates import helper as th
%><%
    OneApi=tags['$OneApi']
    x=tags['$x']
    X=x.upper()
%>
:orphan:

.. _ZE_experimental_image_view_planar:

=============================
 Image View Planar Extension
=============================

%if ver >= 1.5:
This experimental extension is deprecated and replaced by the ${X}_extension_image_view_planar standard extension.
%endif

API
----

* Enumerations


    * ${x}_image_view_planar_exp_version_t

 
* Structures


    * ${x}_image_view_planar_exp_desc_t


