Dnscryptproxy
~~~~~~~~~~~~~

.. csv-table:: Resources (CloakController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","dnscryptproxy","cloak","addCloak",""
    "``POST``","dnscryptproxy","cloak","delCloak","$uuid"
    "``GET``","dnscryptproxy","cloak","getCloak","$uuid=null"
    "``*``","dnscryptproxy","cloak","searchCloak",""
    "``POST``","dnscryptproxy","cloak","setCloak","$uuid"
    "``POST``","dnscryptproxy","cloak","toggleCloak","$uuid"

.. csv-table:: Resources (ForwardController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","dnscryptproxy","forward","addForward",""
    "``POST``","dnscryptproxy","forward","delForward","$uuid"
    "``GET``","dnscryptproxy","forward","getForward","$uuid=null"
    "``*``","dnscryptproxy","forward","searchForward",""
    "``POST``","dnscryptproxy","forward","setForward","$uuid"
    "``POST``","dnscryptproxy","forward","toggleForward","$uuid"

.. csv-table:: Resources (ServerController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","dnscryptproxy","server","addServer",""
    "``POST``","dnscryptproxy","server","delServer","$uuid"
    "``GET``","dnscryptproxy","server","getServer","$uuid=null"
    "``*``","dnscryptproxy","server","searchServer",""
    "``POST``","dnscryptproxy","server","setServer","$uuid"
    "``POST``","dnscryptproxy","server","toggleServer","$uuid"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","dnscryptproxy","service","dnsbl",""

.. csv-table:: Resources (WhitelistController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","dnscryptproxy","whitelist","addWhitelist",""
    "``POST``","dnscryptproxy","whitelist","delWhitelist","$uuid"
    "``GET``","dnscryptproxy","whitelist","getWhitelist","$uuid=null"
    "``*``","dnscryptproxy","whitelist","searchWhitelist",""
    "``POST``","dnscryptproxy","whitelist","setWhitelist","$uuid"
    "``POST``","dnscryptproxy","whitelist","toggleWhitelist","$uuid"

