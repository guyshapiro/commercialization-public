---
author: joshbax-msft
title: DatabaseProjectManager Methods
description: DatabaseProjectManager Methods
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: b3f1bfa8-d6c5-4c21-84e8-1630066a0d82
---

# DatabaseProjectManager Methods


## Public Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CreateDeviceFamily</p></td>
<td><p>Overridden. This method creates a new device family with the given name.</p></td>
</tr>
<tr class="even">
<td><p>CreateProject</p></td>
<td><p>Overridden. This method creates a new Project and adds it to the project collection.</p></td>
</tr>
<tr class="odd">
<td><p>DeleteDeviceFamily</p></td>
<td><p>Overridden. This method deletes a named Device Family.</p></td>
</tr>
<tr class="even">
<td><p>DeleteProject</p></td>
<td><p>Overridden. This method deletes a named project.</p></td>
</tr>
<tr class="odd">
<td><p>Dispose</p></td>
<td><p>This method implements the IDisposable interface. (Inherited from [ProjectManager Class](projectmanager-class.md))</p></td>
</tr>
<tr class="even">
<td><p><strong>Equals</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetDeviceFamilies</strong></p></td>
<td><p>Overridden. This method retrieves a list of available DeviceFamilies.</p></td>
</tr>
<tr class="even">
<td><p>GetFeatures</p></td>
<td><p>Overridden. This method features all of the features stored in the Windows HCK.</p></td>
</tr>
<tr class="odd">
<td><p>GetFilters</p></td>
<td><p>Overridden. This method returns all the filters installed in the system.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetHashCode</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p>GetPlatforms</p></td>
<td><p>Overridden.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetProductTypes</strong></p></td>
<td><p>Overridden.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetProject</strong></p></td>
<td><p>Overridden. This method loads an existing project into the collection.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetProjectInfoList</strong></p></td>
<td><p>Overridden. This method retrieves a list of project information.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetProjectNames</strong></p></td>
<td><p>Overridden. This method retrieves a list of project names.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetProjectSummary</strong></p></td>
<td><p>Overridden.</p></td>
</tr>
<tr class="odd">
<td><p>GetRequirements</p></td>
<td><p>Overridden. This method retrieves the list of requirements in the Windows HCK.</p></td>
</tr>
<tr class="even">
<td><p>GetRootMachinePool</p></td>
<td><p>Overridden. This method retrieves the root machine pool.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetType</strong></p></td>
<td><p>(Inherited from Object)</p></td>
</tr>
<tr class="even">
<td><p><strong>ToString</strong></p></td>
<td><p>(Inherited from Object)</p></td>
</tr>
</tbody>
</table>

 

## Protected Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Dispose</p></td>
<td><p>Overridden. This method implements the <strong>IDisposable</strong> interface.</p></td>
</tr>
<tr class="even">
<td><p><strong>Finalize</strong></p></td>
<td><p>This method finalizes an instance of the <strong>ProjectManager</strong> class. (Inherited from [ProjectManager Class](projectmanager-class.md))</p></td>
</tr>
<tr class="odd">
<td><p><strong>MemberwiseClone</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
</tbody>
</table>

 

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20DatabaseProjectManager%20Methods%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



