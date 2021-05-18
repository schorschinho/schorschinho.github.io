---
layout: page
title: Osprey
description: Open-source MATLAB software for processing, modeling, and quantification of magnetic resonance spectroscopy data.
img: /assets/img/project-osprey/04-fit-mets.png
importance: 1
category: work
---
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/schorschinho/osprey)](https://github.com/schorschinho/osprey/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/schorschinho/osprey)](https://github.com/schorschinho/osprey/releases)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/schorschinho/osprey?foo=bar)](https://github.com/schorschinho/osprey/commits/develop)
[![GitHub last commit](https://img.shields.io/github/last-commit/schorschinho/osprey)](https://github.com/schorschinho/osprey/commits/develop)
[![Website](https://img.shields.io/website?down_color=lightgrey&down_message=offline&up_color=green&up_message=online&url=https%3A%2F%2Fschorschinho.github.io%2Fosprey)](https://schorschinho.github.io/osprey)
[![License](https://img.shields.io/github/license/schorschinho/osprey)](https://github.com/schorschinho/osprey/blob/develop/LICENSE.md)

<p style="text-align: center; font-size: large">
<img class="img-fluid rounded z-depth-1 mh-25" src="{{ '/assets/img/osprey.png' | relative_url }}" alt="" style="width: 25%" title="Download Osprey"/>
<br>
<a href="https://github.com/schorschinho/osprey/releases" target="_blank">Download the latest Osprey release</a>
<br>
<a href="https://schorschinho.github.io/osprey/" target="_blank">Read the Osprey documentation</a>
<br>
<a href="https://forum.mrshub.org/c/mrs-software/osprey/10" target="_blank">Visit the Osprey support forum at the MRSHub</a>
</p>



One of the challenges of magnetic resonance spectroscopy research is the complexity and abundance of analysis methods. Most researchers have created their own analysis pipelines and scripts to transform raw data into metabolite concentrations, often using code that has grown somewhat organically over the course of many years. Perhaps it should not be surprising that the results that different researchers come up with do not typically agree very well.

We actively develop Osprey, our all-in-one software environment for state-of-the art processing and quantitative analysis of in-vivo magnetic resonance spectroscopy (MRS) data. Osprey covers all steps of modern MRS data analysis, [in compliance with 2020 expert consensus recommendations](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/full/10.1002/nbm.4257){:target="_blank"} and adhering to [minimum reporting standards](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/10.1002/nbm.4484){:target="_blank"}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/project-osprey/04-process-mets.png' | relative_url }}" alt="" title="OspreyProcess"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/project-osprey/04-fit-mets.png' | relative_url }}" alt="" title="OspreyFit"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/project-osprey/04-seg.png' | relative_url }}" alt="" title="OspreySeg"/>
    </div>
</div>
<div class="caption">
    The Osprey GUI. Left: Processing tab with individual transients before and after frequency-and-phase correction. Middle: Integrated linear-combination modeling module. Right: Co-registration and tissue class segmentation (interfaced with SPM12).
</div>

Our research is equally focused on the development and the application of advanced methodology. We created Osprey to provide a tool that can be applied out of the box by non-expert MRS users to analyze the most common MRS acquisition techniques. At the same time, the workflow is designed in a modular way to allow Osprey to easily expand and adapt to new acquisition and analysis methods.

Osprey will always be entirely free and open-source. You can download the latest release from the Osprey GitHub repository.

<p style="text-align: center; font-size: large">
<img class="img-fluid rounded z-depth-1 mh-25" src="{{ '/assets/img/osprey.png' | relative_url }}" alt="" style="width: 25%" title="Download Osprey"/>
<br>
<a href="https://github.com/schorschinho/osprey/releases" target="_blank">Download the latest Osprey release</a>
<br>
<a href="https://schorschinho.github.io/osprey/" target="_blank">Read the Osprey documentation</a>
<br>
<a href="https://forum.mrshub.org/c/mrs-software/osprey/10" target="_blank">Visit the Osprey support forum at the MRSHub</a>
</p>
