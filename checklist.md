# Data Centre Migration Discovery Phase Information Gathering Checklist

- [ ] Device Name
    _What is the device name_
- [ ] Device Type/Model
    _What is this device, physical server, virtual, networking switch_
- [ ] Firmware versions (if appropriate)
    _A check in on firmware versions will help you understand if you may hit any compatibility issues etc_
- [ ] Operating System
    _What is the operating system version, again this will help you understand if you may hit any compatibility issues etc_
- [ ] Physical Location
    _Where is the device physically location in your datacentre_
- [ ] What does the device/server do?
    _What does this server or device do? Is it the server that runs your payroll system? Or the one that hosts your canteen lunch menu?_
- [ ] Workload owner & contact details
    _Who in the business is the owner of this workload, who needs to authorise outages, changes etc_
- [ ] Workload manufacturer
    _If you are running an application on the server, who made it, is it external? is it internal?_
- [ ] Workload lifecycle
    _Is the workload a long term one, one that will be replaced or retired in a few months_
- [ ] Support contract information (hardware)
    _Contact information for your hardware vendor support_
- [ ] Support contract information (workload)
    _Contact information for your workload vendor support_
- [ ] Environment (prod, dev, test, etc)
    _Which environment does this server/device sit in?_
- [ ] Dependencies (what does this server interact with)
    _What does this server/device/workload interact with, what does it rely on what what relies on it? Data information (connection details, sources, etc)_
- [ ] Availability
    _Does the workload need to be available 24/7? Or are there times when an outage can be accepted?_
- [ ] Backup information
    _What is backed up and needs to be protected on this workload_
- [ ] Backup schedule
    _What is the backup window for this workload_
- [ ] Criticality
    _How important is this workload to the business?_
- [ ] Disaster Recovery information
    _What current plans are in place should the worst happen?_
- [ ] System and/or network diagrams
    _Diagrams of your environment can be useful quick reference guides_
- [ ] Sensitive Data/Personally Identifiable Information (PII) being stored
    _Is the system storing sensitive data and as such will need to be considered when moving to the Cloud?_
