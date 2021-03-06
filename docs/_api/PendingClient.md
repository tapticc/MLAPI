---
title: PendingClient
name: PendingClient
permalink: /api/pending-client/
---

<div style="line-height: 1;">
	<h2 markdown="1">PendingClient ``class``</h2>
	<p style="font-size: 20px;"><b>Namespace:</b> MLAPI.Connection</p>
	<p style="font-size: 20px;"><b>Assembly:</b> MLAPI.dll</p>
</div>
<p>A class representing a client that is currently in the process of connecting</p>

<div>
	<h3 markdown="1">Public Fields</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``ulong`` ClientId;</b></h4>
		<p>The ClientId of the client</p>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``byte[]`` AesKey;</b></h4>
		<p>The current AesKey</p>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public [``State``](/MLAPI/api/state/) ConnectionState;</b></h4>
		<p>The state of the connection process for the client</p>
	</div>
</div>
<br>
<div>
	<h3>Public Constructors</h3>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``PendingClient``](/MLAPI/api/pending-client/)();</b></h4>
	</div>
</div>
<br>
<div>
	<h3 markdown="1">Inherited Methods</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``string`` ToString();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` Equals(``object`` obj);</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object`` obj</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``int`` GetHashCode();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``Type`` GetType();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
</div>
<br>
