---
title: Getting started overview
layout: home
sidebar: home_sidebar
type: homepage
toc: false
---

{% if site.audience == "administrators" %}
hi admins
{% elsif site.audience == "analysts" %}
hi analysts
{% endif %}

<div class="jumbotron">
  <h1>Ideas @ MSE & CS = Creativity</h1>
  <p>An academic writing system based on Jekyll and GitHUb </p>
</div>

<div class="row">
        <div class="col-lg-12">
            <h2 class="page-header">Notes@NUS</h2>
        </div>
        <!--first-->
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                	<span class="fa-stack fa-5x">
                	<img title="my sample page" src="{{ "/images/TEM.jpg" | prepend: site.baseurl }}" class="note-photo">
                    </span>
                </div>
                <div class="panel-body">
                    <h4>Electron Microscopy</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <!--second-->
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <span class="fa-stack fa-5x">
                          <img title="my sample page" src="{{ "/images/2D.jpg" | prepend: site.baseurl }}" class="note-photo">
                    </span>
                </div>
                <div class="panel-body">
                    <h4>2D Materials</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <!--Third-->
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <span class="fa-stack fa-5x">
                          <img title="my sample page" src="{{ "/images/QM.jpg" | prepend: site.baseurl }}" class="note-photo">
                    </span>
                </div>
                <div class="panel-body">
                    <h4>Quantum Mechanics</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <!--fourth-->
        <div class="col-md-3 col-sm-6">
            <div class="panel panel-default text-center">
                <div class="panel-heading">
                    <span class="fa-stack fa-5x">
                          <img title="my sample page" src="{{ "/images/workflow.png" | prepend: site.baseurl }}" class="note-photo">
                    </span>
                </div>
                <div class="panel-body">
                    <h4>Academic Workflow</h4>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
</div>


