.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. ==================================================
.. DEFINE SOME TEXTROLES
.. --------------------------------------------------
.. role::   underline
.. role::   typoscript(code)
.. role::   ts(typoscript)
   :class:  typoscript
.. role::   php(code)


Reference
^^^^^^^^^

.. ### BEGIN~OF~TABLE ###

.. t3-field-list-table::
 :header-rows: 1

 - :Property:
         Property

   :Data type:
         Data type

   :Description:
         Description

   :Default:
         Default


 - :Property:
         width

   :Data type:
         int+

   :Description:
         The width of the embedded video in px.

   :Default:
         560


 - :Property:
         height

   :Data type:
         int+

   :Description:
         The height if the embedded video in px.

         To keep the aspect of a video, open the youtube-link of the video, go
         to “share”->”embed” and select “usedefinde size” for videosize.

         Entering the width will provide the right height.

   :Default:
         315


 - :Property:
         html5

   :Data type:
         boolean

   :Description:
         Embed videos as html5(True (1) is recommanded to support as many
         modern devices as possible)

   :Default:
         1


 - :Property:
         cssFile

   :Data type:
         file

   :Description:
         Path to css file

   :Default:
         EXT:jh_simple_youtube/Resources/Public/css/tx_jhsimpleyoutube.css


.. ###### END~OF~TABLE ######

[tsref:plugin.tx\_jhsimpleyoutube.settings]

