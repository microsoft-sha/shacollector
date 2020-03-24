# shacollector (Storage and High Availability area log collection tool)<BR>
<pre>
Usage:<BR>
  shacollector.bat trace [trace option] start [output folder (default c:\mslog)]<BR>
  shacollector.bat trace [trace option] stop<BR>
  shacollector.bat trace [trace option] boot [output folder (default c:\mslog)]<BR>
  shacollector.bat trace [trace option] delete<BR>
<BR>
  shacollector.bat perf perfmon start [output folder (default c:\mslog)] interval [sample interval [hh:mm:ss] (ex. 00:00:15) default 15sec]<BR>
  shacollector.bat perf cpu start [output folder (default c:\mslog)]<BR>
  shacollector.bat perf cpu stop<BR>
  shacollector.bat perf memory start [output folder (default c:\mslog)] tag "POOL TAG (ex. FMfn)"<BR>
  shacollector.bat perf memory stop<BR>
  shacollector.bat perf disk start [output folder (default c:\mslog)]<BR>
  shacollector.bat perf disk stop<BR>
  shacollector.bat perf delay start [output folder (default c:\mslog)]<BR>
  shacollector.bat perf delay stop<BR>
<BR>
  shacollector.bat support all [output folder (default c:\mslog)]<BR>
  shacollector.bat support basic [output folder (default c:\mslog)]<BR>
  shacollector.bat support [supportlog option] [output folder (default c:\mslog)]<BR>
<BR>
Option:<BR>
   trace log option:<BR>
      storage   collecting storage drivers trace. (ex storport.sys, classpnp.sys ...)<BR>
      storport  collecting storport driver trace.<BR>
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
      network   collecting Network driver trace.<BR>
      iscsi     collecting iSCSI driver trace.<BR>
      csv       collecting CSV drivers trace.<BR>
      wmi       collecting WMI services trace.<BR>
      rpc       collecting RPC services trace.<BR>
      hyper-v   collecting Hyper-V modules trace.<BR>
      cluster   collecting Failover Clustering trace (included netft trace).<BR>
      space     collecting Storage Space trace.<BR>
      storagereplica     collecting Storage Replica trace.<BR>
      packet    collecting Network Packet Capture. (Windows Server 2008 R2 or later)<BR>
      procmon   collecting Process Monitor log of Sysinternals.<BR>
      psr       collecting Problems Steps Recorder log.<BR>
<BR>
   performance log option:<BR>
      perfmon   collecting Performance Monitor log. default sample interval is 15sec.<BR>
      cpu       collecting CPU perf logs with Xperf.<BR>
      memory    collecting Memory perf logs with Xperf.<BR>
      disk      collecting Disk perf logs with Xperf.<BR>
      delay     collecting Delay perf logs with Xperf.<BR>
<BR>
   support log option:<BR>
      all             collecting all support logs.<BR>
         included cluster, disk, diskshadow, driverinfo, eventlog, fltmc, fsrm, handle, hyper-v, iscsi, network, nfs, registry, storagereplica, system, taskscheduler, virtualfc, vss<BR>
      basic           collecting basic support logs.<BR>
         included disk, driverinfo, eventlog, fltmc, network, system, vss<BR>
      cluster         collecting cluster information logs.<BR>
      disk            collecting disk information logs.<BR>
      diskshadow      collecting diskshadow information logs.<BR>
      driverinfo      collecting driver information logs.<BR>
      drive-space     collecting drive space information logs.<BR>
      eventlog        collecting eventlog information logs.<BR>
      fltmc           collecting filter driver information logs.<BR>
      fsrm            collecting fsrm information logs.<BR>
      handle          collecting file handle information.<BR>
      hyper-v         collecting hyper-v information logs.<BR>
      iscsi           collecting iscsi information logs.<BR>
      network         collecting network information logs.<BR>
      nfs             collecting nfs information logs.<BR>
      registry        collecting registry information logs.<BR>
      storagereplica  collecting Storage Replica information logs.<BR>
      system          collecting system information logs.<BR>
      taskscheduler   collecting task scheduler information logs.<BR>
      virtualfc       collecting virtual fc information.<BR>
      vss             collecting vss information logs.<BR>
      setup           collecting setup information logs.<BR>
      fsi             collecting file system information logs.<BR>
      crash           generate blue screen of death (BSOD).<BR>
</pre>
