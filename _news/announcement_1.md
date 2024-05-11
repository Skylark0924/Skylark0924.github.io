---
layout: post
title: Rofunc v0.0.2.6 is released with plenty of robot skill learning examples!
date: 2024-01-24 16:11:00-0400
inline: false
related_posts: false
---

Rofunc v0.0.2.6 is released with plenty of robots skill learning examples! :sparkles: :rocket:

---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/logo8.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

# Rofunc: The Full Process Python Package for Robot Learning from Demonstration and Robot Manipulation

[![Release](https://img.shields.io/github/v/release/Skylark0924/Rofunc)](https://pypi.org/project/rofunc/)
![License](https://img.shields.io/github/license/Skylark0924/Rofunc?color=blue)
![](https://img.shields.io/github/downloads/skylark0924/Rofunc/total)
[![](https://img.shields.io/github/issues-closed-raw/Skylark0924/Rofunc?color=brightgreen)](https://github.com/Skylark0924/Rofunc/issues?q=is%3Aissue+is%3Aclosed)
[![](https://img.shields.io/github/issues-raw/Skylark0924/Rofunc?color=orange)](https://github.com/Skylark0924/Rofunc/issues?q=is%3Aopen+is%3Aissue)
[![Documentation Status](https://readthedocs.org/projects/rofunc/badge/?version=latest)](https://rofunc.readthedocs.io/en/latest/?badge=latest)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FSkylark0924%2FRofunc%2Fbadge%3Fref%3Dmain&style=flat)](https://actions-badge.atrox.dev/Skylark0924/Rofunc/goto?ref=main)

> **Repository address: [https://github.com/Skylark0924/Rofunc](https://github.com/Skylark0924/Rofunc)** <br>
> **Documentation: [https://rofunc.readthedocs.io/](https://rofunc.readthedocs.io/)**


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURIQbSoftHandSynergyGraspSpatulaRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURIQbSoftHandSynergyGraspPower_drillRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURIQbSoftHandSynergyGraspPhillips_Screw_DriverRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURIQbSoftHandSynergyGraspLarge_clampRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURICoffeeStirring.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURIScrew.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/CURITaichiPushingHand.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidFlipRofuncRLAMP.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidDanceRofuncRLAMP.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidRunRofuncRLAMP.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidASEHeadingSwordShieldRofuncRLASE.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidASEStrikeSwordShieldRofuncRLASE.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/HumanoidASELocationSwordShieldRofuncRLASE.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/BiShadowHandLiftUnderarmRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/BiShadowHandDoorOpenOutwardRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/doc/img/task_gif3/BiShadowHandSwingCupRofuncRLPPO.gif" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>