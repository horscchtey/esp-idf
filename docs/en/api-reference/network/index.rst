Networking APIs
***************

:link_to_translation:`zh_CN:[中文]`

Wi-Fi
=====

.. toctree::
    :maxdepth: 1

    esp_now
    esp-wifi-mesh
    esp_smartconfig
    esp_wifi
    esp_dpp

Code examples for the Wi-Fi API are provided in the :example:`wifi` directory of ESP-IDF examples.

Code examples for ESP-WIFI-MESH are provided in the :example:`mesh` directory of ESP-IDF examples.


Ethernet
========

.. toctree::
   :maxdepth: 1

   esp_eth

Code examples for the Ethernet API are provided in the :example:`ethernet` directory of ESP-IDF examples.

Thread
==========

.. toctree::
   :maxdepth: 1

   esp_openthread

Thread is an IPv6-based mesh networking technology for IoT.
Code examples for the Thread API are provided in the :example:`openthread` directory of ESP-IDF examples.

ESP-NETIF
=========

.. toctree::
   :maxdepth: 1

   esp_netif

IP Network Layer
================

.. toctree::
    :hidden:

    tcpip_adapter_migration
    esp_netif_driver

Code examples for TCP/IP socket APIs are provided in the :example:`protocols/sockets` directory of ESP-IDF examples.

The TCP/IP Adapter (legacy network interface library) has been deprecated, please consult the :doc:`/api-reference/network/tcpip_adapter_migration` to update existing IDF applications.

Application Layer 
=================

Documentation for Application layer network protocols (above the IP Network layer) are provided in :doc:`../protocols/index`.
