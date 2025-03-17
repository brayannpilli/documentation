:show-content:

.. |VOIP| replace:: :abbr:`VoIP (Voice over Internet Protocol)`

===================================
VoIP (Voice over Internet Protocol)
===================================

|VOIP| in Odoo enables businesses to handle calls over the internet, integrating seamlessly with
other Odoo apps for efficient communication. Users can make and receive calls, log interactions, and
automate call routing, all within Odoo. With support for providers like Axivox and OnSIP, it offers
flexibility while centralizing customer interactions.

Overview
========

By unifying telephony with Odoo's apps, |VOIP| improves sales and support efficiency, enhances call
tracking, and reduces costs by eliminating traditional phone systems. Features like call recording
and analytics optimize performance, while seamless integration boosts productivity and customer
satisfaction.

.. cards::
   .. card:: VoIP widget
      :target: voip/voip_widget

      Get oriented with the features of the VoIP widget, like what actions can be taken during a
      call.

   .. card:: Devices and integrations
      :target: voip/devices_integrations

      Learn about accessing the VoIP widget from differet devices (like phones) and apps (like
      Linphone).

   .. card:: Make, receive, transfer, and forward calls
      :target: voip/transfer_forward

      Learn how to interact with the VoIP widget and take essential actions, like call forwarding.

VoIP terms
----------

- **VoIP**: Voice over Internet Protocol. Technology that is used to handle calls that are not made
  from a phone line.
- **SIP**: Session Initiation Protocol. Technology included in VoIP that specifically handles the
  setup, management, and termination of calls.
- **Call queue**: A system to route calls (usually in a support team). This allows customers to wait
  for help if no support agents are available.
- **Dial plans**: A system to define how VoIP calls are routed, based on set rules.

VoIP configuration
==================

Configuring |VOIP| in Odoo will require a |VOIP| service provider. Learn more about :doc:`signing up
for a VoIP service provider <voip/voip_widget>`. While Odoo provides the integrated |VOIP| tool to
make calls and schedule activities from within the database, a separate |VOIP| service provider is
required to make the calls themselves.

Odoo has two partnered VoIP providers: `Axivox <https://www.axivox.com/>`_ and `OnSIP
<https://www.onsip.com/>`_. Learn more about using their services to configure VoIP below.

.. cards::
   .. card:: Axivox configuration
      :target: voip/axivox

      Learn how to set up Axivox in Odoo. This includes adding users to Axivox, setting up call
      queues, and more.

   .. card:: OnSIP configuration
      :target: voip/onsip

      Learn how to set up OnSIP in Odoo. This includes entering OnSIP credentials into Odoo and
      handling troubleshooting.

.. seealso::
   For more information, reference the `Odoo eLearning (video tutorials) on VoIP
   <https://www.odoo.com/slides/voip-voice-over-ip-315>`_

.. toctree::
   :titlesonly:

   voip/onsip
   voip/axivox
   voip/voip_widget
   voip/devices_integrations
   voip/transfer_forward
