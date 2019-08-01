shacollector (Storage and High Availability area log collection tool)
Usage:
  shacollector.bat [option] start [output folder (default c:\mslog)]
  shacollector.bat [option] stop
  shacollector.bat [option] boot [output folder (default c:\mslog)]
  shacollector.bat [option] delete
  shacollector.bat support [output folder (default c:\mslog)]

Option:
   storage   collecting storage drivers trace. (ex storport.sys, classpnp.sys ...)
   usb       collecting USB drivers trace.
   pnp       collecting Plug and Play drivers trace.
   com       collecting COM/COM+ services trace.
   vds       collecting VDS services trace. (Windows Server 2012 or later)
   vss       collecting VSS services trace. (Windows Server 2008 R2 or later)
   wsb       collecting Windows Server Backup modules trace. (Windows Server 2008 R2 or later)
   cdrom     collecting CD/DVD modules trace.
   ata       collecting ATAPort drivers trace.
   fsrm      collecting FSRM drivers trace.
   dedup     collecting Dedup drivers trace. (Windows Server 2012 or later)
   nfs       collecting NFS services trace.
   iscsi     collecting iSCSI driver trace.
   csv       collecting CSV drivers trace.
   wmi       collecting WMI services trace.
   rpc       collecting RPC services trace.
   hyper-v   collection Hyper-V modules trace.
   cluster-manager     collection Failover Clustering Manager trace.
   space     collecting Storage Space trace.
   storagereplica     collecting Storage Replica trace.
   packet    collecting Network Packet Capture. (Windows Server 2008 R2 or later)
   support   collecting support information logs.
