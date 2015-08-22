---
layout: default
title: Map
permalink: /map/
---

<h1>Map</h1>

<div class="alert alert-info"><b>Please notice</b>: this website is under development. More information on the project and additional pages will follow in the next days.</div>

<p>This map allows you get an overview and browse through the data that is being collaboratively collected on surveillance, privacy, and digital threats to civil society. Click on a country to get an overview of the available information.</p>

<center><div id="map" style="position: relative; width: 100%; height: 600px;"></div></center>

<div class="modal fade" id="modal">
    <div class="modal-dialog">
    <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
            <h4 class="modal-title">{{country}}</h4>
        </div>
        <div class="modal-body">
            <p>We have records for {{number}} targeted attack/s in {{country}}, using the following malware families {{list of unique "family" names}}.</p>
            <p>We have records for {{number}} surveillance vendors in {{country}}.</p>
            <p>We have records for {{number}} surveillance resellers in {{country}}.</p>
            <hr />
            <p>For more information, <a href="/country/#{{country code}}">view the country page related to {{country}}</a>.</p>
        </div>
    </div>
  </div>
</div>