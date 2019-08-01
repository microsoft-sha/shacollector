# shacollector (Storage and High Availability area log collection tool)
Usage:<BR>
	shacollector.bat [option] start [output folder (default c:\mslog)]<BR>
	shacollector.bat [option] stop<BR>
  shacollector.bat [option] boot [output folder (default c:\mslog)]<BR>
  shacollector.bat [option] delete<BR>
  shacollector.bat support [output folder (default c:\mslog)]<BR>
	<BR>
Option:<BR>
   storage   collecting storage drivers trace. (ex storport.sys, classpnp.sys ...)<BR>
   usb       collecting USB drivers trace.<BR>
   pnp       collecting Plug and Play drivers trace.<BR>
   com       collecting COM/COM+ services trace.<BR>
   vds       collecting VDS services trace. (Windows Server 2012 or later)<BR>
   vss       collecting VSS services trace. (Windows Server 2008 R2 or later)<BR>
   wsb       collecting Windows Server Backup modules trace. (Windows Server 2008 R2 or later)<BR>
   cdrom     collecting CD/DVD modules trace.<BR>
   ata       collecting ATAPort drivers trace.<BR>
   fsrm      collecting FSRM drivers trace.<BR>
   dedup     collecting Dedup drivers trace. (Windows Server 2012 or later)<BR>
   nfs       collecting NFS services trace.<BR>
   iscsi     collecting iSCSI driver trace.<BR>
   csv       collecting CSV drivers trace.<BR>
   wmi       collecting WMI services trace.<BR>
   rpc       collecting RPC services trace.<BR>
   hyper-v   collection Hyper-V modules trace.<BR>
   cluster-manager     collection Failover Clustering Manager trace.<BR>
   space     collecting Storage Space trace.<BR>
   storagereplica     collecting Storage Replica trace.<BR>
   packet    collecting Network Packet Capture. (Windows Server 2008 R2 or later)<BR>
   support   collecting support information logs.<BR>
