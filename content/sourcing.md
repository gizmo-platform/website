---
title: Sourcing Parts
date: 2024-08-15T23:34:30-05:00
---

The Gizmo platform is made up of several components sourced from
various suppliers.  We currently don't provide commercial sourcing of
these parts, though are evaluating partner organizations to provide a
more streamlined experience.  We expect to have development on a
streamlined purchasing experience for the Gizmo itself in the Spring
of 2025, and appologize for any difficulties this delay causes you.

## The Gizmo Itself

The Gizmo itself is Open Source hardware available to anyone under the
terms of the CERN-OHL-P-2.0 license.  This is a permissive license
that allows you to manufacture your own boards (even commercially)
with recognition that the board was designed by the authors listed on
the license.

If you really, _really_, want a Gizmo now, and are willing to put in some
work to get it, you can go directly to our manufacturing partner
PCBWay and place an order.  Some things to keep in mind while doing
this:

  * You'll need to place a minimum order of 5 boards.
  * Make sure that you specify you want boards *AND* assembly when
    placing your order.
  * These are the raw boards, you'll still need to source a case and
    Raspberry Pi Pico modules.
  * When prompted:
    * You want resin-filled vias.
    * V-Cut panelization is preferred.
    * You will accept X-Out boards.

If this doesn't deter you, you can use [this
link](https://www.pcbway.com/project/shareproject/Gizmo_Platform_Carrier_Board_v1_0_28f40401.html)
to go to PCBWay and put an order in.  Lead time is about a month once
your order is paid for.  If this process is more than you want to deal
with, we highly encourage you to wait until Spring of 2025 when we
expect to have an optimized sourcing process.

## The Driver's Station

The Driver's Station is comprised of a Raspberry Pi Zero 2 W, case,
USB and Ethernet breakout, and a Logitech F310 gamepad.  You can
source most of these parts from wherever you want, but here are some
non-affiliate links to the case with USB and Ethernet breakout, and
the Logitech controller.

  * [Case](https://www.amazon.com/dp/B09MBBFM8Q)
  * [Gamepad](https://www.amazon.com/dp/B003VAHYQY)

You'll also need one each of the Raspberry Pi Pico W and Raspberry Pi
Pico H boards.  We source ours from PiShop which is an authorized
reseller of Raspberry Pi Products and has a very optimized process for
working with non-profits and schools.

  * [Pico W](https://www.pishop.us/product/raspberry-pi-pico-wh-pre-soldered-headers/)
  * [Pico H](https://www.pishop.us/product/raspberry-pi-pico-h-pre-soldered-headers/)

The user processor is the Pico H.  While in normal operation its
pretty hard to damage the Pico, we socket these components for a
reason and you may consider picking up a spare or two so that if you
inadvertently let out the magic smoke that makes the electronics work,
you have an extra processor on hand to swap in.

## Field Management System

If you're planning to run a competition with the Gizmo, you'll also
need our Field Management System.  This is a dedicated set of network
components and a computer that runs the entire competition system.
Our FMS is designed to run competitions with 4 robots per field
identified by unique colors.  We currently specify the following
components, and you can use these non-affiliate links to find exactly
the same hardware our team uses to test.

  * [Scoring Box](https://www.amazon.com/dp/B07HHF2C48) - You need one
    of these per competition environment that you want to run.  It
    forms the core of the network and supports up to 3 concurrent
    fields.  If you need more than this, reach out to us and we can
    work with you to make giant-scale events a reality.

  * [Field Box](https://www.amazon.com/dp/B019PCF3QY) - As the name
    implies, you need one of these per field.  This contains the
    managed radio that talks to each robot and one port per quadrant.

  * [FMS
    Workstation](https://www.pishop.us/product/raspberry-pi-400/) -
    This is the dedicated computer that runs our software to control
    the entire system.  You'll need one of these plus at least one
    HDMI capable computer monitor to plug it into.  We specify and
    support the Raspberry Pi 400, but you should also be able to use a
    Raspberry Pi 4 or 5 for this function.  If you require support for
    your events, we ask that you stay within our specified hardware
    lists, which at this time only include the Raspberry Pi 400.

If you're looking to reduce the cost of the Field Management System,
its possible to use the non-PoE version of the Scoring table box, but
this does mean you'll need to get power to the Field Box(s).
