# shacollector (Storage and High Availability area log collection tool)
Usage:<BR>
	shacollector.bat [option] start [output folder (default c:\mslog)]<BR>
shacollector.bat [option] stop (hype-v, ***-perf and cluster-manager)<BR>
  shacollector.bat [option] boot [output folder (default c:\mslog)]<BR>
  shacollector.bat [option] delete<BR>
  shacollector.bat perfmon start "output folder" "sample interval [hh:mm:ss] (ex. 00:00:15)"<BR>
  shacollector.bat memory-perf start "output folder" "POOL TAG (ex. FMfn)"<BR>
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
   procmon   collecting Process Monitor log of Sysinternals.<BR>
   perfmon   collecting Performance Monitor log. default sample interval is 15sec.<BR>
   cpu-perf     collection CPU perf logs with Xperf.<BR>
   memory-perf     collection Memory perf logs with Xperf.<BR>
   disk-perf     collection Disk perf logs with Xperf.<BR>
   delay-perf     collection Delay perf logs with Xperf.<BR>
   packet    collecting Network Packet Capture. (Windows Server 2008 R2 or later)<BR>
   support   collecting support information logs.<BR>
