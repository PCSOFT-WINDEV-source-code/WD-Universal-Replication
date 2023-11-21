  
<span style="font-family:Arial sans-serif;font-size:16px;">WD Universal Replication</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">This examples explains how to use the universal replication to synchronize data of different sites.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The universal replication is used to synchronize the data of a site (master site) with the same data of one or more replicated sites (subscriber sites). The data structures are identical on each site but they can be exploited via different data managers. HFSQL Classic and Access will be used in this example.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">The example presents the processes that must be included in your applications to allow the user, via a simple action (menu, button, ...), to:</span>

<span style="font-family:Arial sans-serif;font-size:14px;">- create a master replica, </span>

<span style="font-family:Arial sans-serif;font-size:14px;">- create one or more subscriber replicas, </span>

<span style="font-family:Arial sans-serif;font-size:14px;">- see and modify the data of these replicas, </span>

<span style="font-family:Arial sans-serif;font-size:14px;">- export the created or modified data to a site (portable replica), </span>

<span style="font-family:Arial sans-serif;font-size:14px;">- import the created or modified data into another site...</span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="text-decoration:underline;font-family:Arial sans-serif;font-size:10px;">Conditions of Use.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">This program is supplied for training purposes.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">The use of this program is the responsibility of the user. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">PC SOFT will not be liable for damage or loss of any nature whatsoever, including data loss, corruption or deterioration as a result of using this program.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Any person owning a WINDEV 28 US license is authorized to use and/or modify the program and to use it in their own applications. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">In this case all references to PC SOFT and/or to WinDev or WebDev must be removed.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">You may not distribute or sell this example program without substantial modification or include it in another application unless the application is very large.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">No Hot Line Support is available for this program.</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">CAUTION: Many users may have modified this program. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Make sure that you are working with the original version of this program.</span>

  
  
  
  