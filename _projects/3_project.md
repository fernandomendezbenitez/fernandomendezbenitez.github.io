---
layout: page
title: SABR Calibration and Interpolation at Non-Tenor Dates
description: Total-variance interpolation with recalibration as a theoretically motivated challenger to industry-standard SABR parameter interpolation
img: assets/img/3.jpg
importance: 3
category: work
---

## Overview

BDO research (2025) assessing the accuracy of industry-standard SABR parameter interpolation at non-tenor dates, and proposing total-variance interpolation with subsequent recalibration as a theoretically motivated alternative.

## Motivation

Practitioners routinely interpolate SABR parameters linearly or cubically across tenors to price instruments at intermediate dates. This approach lacks theoretical grounding and introduces systematic mispricing that is difficult to detect without a principled challenger methodology.

## Key Findings

The total-variance interpolation approach — interpolating in total variance space before recalibrating SABR parameters — consistently outperforms both linear and cubic parameter interpolation. RMSEs under the incumbent approaches are approximately 1.7x and 1.9x higher respectively. The challenger methodology was adopted in production, improving the accuracy of BDO's independent model valuations across the rates book.

