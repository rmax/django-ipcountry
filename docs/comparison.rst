Current Ip-to-Country Apps
--------------------------

* django-iptocountry
    * URL: http://code.google.com/p/django-iptocountry/
    * License: GPL v2
    * Updated: May 29, 2008

* django-countryip
    * URL: http://code.google.com/p/django-countryip/
    * License: MIT
    * Updated: Jun 15, 2008

* django-ip2country
    * URL: http://code.google.com/p/django-ip2country/
    * License: GPL v3
    * Updated: Sep 23, 2009


.. list-table:: Features Matrix
    :widths: 20 15 15 15
    :header-rows: 1

    * - feature
      - iptocountry
      - countryip
      - ip2country
    * - maxmind support
      - no
      - yes (csv)
      - no
    * - ip-to-country csv support
      - yes
      - no
      - yes
    * - models
      - IpToCountry
      - Country & IPRange
      - Ip2Country
    * - big / long integer
      - no (char)
      - needs column alter
      - yes (bigint)
    * - includes database
      - yes (csv & fixture)
      - no
      - no
    * - imports csv
      - yes
      - yes
      - yes
    * - downloads latest db
      - no
      - no
      - yes
    * - country flag templatetag
      - yes
      - no
      - no
    * - includes country flag images
      - yes
      - no
      - no
    * - django admin integration
      - yes (pre-1.0 style)
      - no
      - yes

