.. Copyright (C) 2015, Wazuh, Inc.

.. meta::
  :description: The Wazuh dashboard gives you a quick view of your agents, alerts, and cluster. Learn how to configure its features in this section. 
  
.. _wazuh_dashboard_settings:

Settings
========

The *Settings* page allows you to configure and customize your Wazuh dashboard experience.

API
---

In this section, you can list all your inserted API credentials. The star icon indicates the currently used API to show information on the app. Each entry has multiple available actions to manage it. Keep in mind that a working API is needed to add or edit an entry. Check your API connection status before adding them to the app.

.. thumbnail:: ../../images/kibana-app/features/settings/api.png
  :align: center
  :width: 100%

Modules
-------

Wazuh dashboard provides multiple integrations and capabilities to monitor and analyze your hosts. You can enable multiple modules to visualize tailored dashboards, which provide rich and useful information. Some of these extensions are disabled by default because you have to previously enable them on your manager configuration in order to generate alerts.

.. thumbnail:: ../../images/kibana-app/features/settings/extensions.png
  :align: center
  :width: 100%

Configuration
-------------

You can take a quick look at the Wazuh dashboard configuration file here. The documentation for the ``wazuh.yml`` file can be found in the config section.

.. thumbnail:: ../../images/kibana-app/features/settings/configuration.png
  :align: center
  :width: 100%

Logs
----

The Wazuh dashboard stores log information on the ``/usr/share/wazuh-dashboard/data/wazuh/logs/wazuhapp.log`` file. These logs can be helpful for troubleshooting purposes. 

.. thumbnail:: ../../images/kibana-app/features/settings/logs.png
  :align: center
  :width: 100%

About
-----

This section provides information about your currently installed Wazuh dashboard package, such as version, revision, and installation date. If you want to discover what's new on each release, you can go to our `Changelog file <https://github.com/wazuh/wazuh-dashboard-plugins/blob/master/CHANGELOG.md>`_ to check it out.

.. thumbnail:: ../../images/kibana-app/features/settings/about.png
  :align: center
  :width: 100%
