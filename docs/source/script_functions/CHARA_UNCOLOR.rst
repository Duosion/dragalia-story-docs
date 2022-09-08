.. _CHARA_UNCOLOR:

CHARA_UNCOLOR
========================

.. code-block:: text

	CHARA_UNCOLOR(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_UNCOLOR(CID):
		chara_color(CID, 0, TYPE_COLOR, 255, 255, 255)
		chara_color(CID, 0, TYPE_COLOR_TOP, 255, 255, 255)
		chara_color(CID, 0, TYPE_COLOR_BOTTOM, 255, 255, 255)
		chara_color(CID, 0, TYPE_COLOR_LASTMUL, 255, 255, 255)
		chara_contrast(CID, 1)
		chara_saturation(CID, 1)
		chara_brightness(CID, 1)
		wait(0)

References
-------------
* :ref:`chara_color`
* :ref:`chara_contrast`
* :ref:`chara_saturation`
* :ref:`chara_brightness`
* :ref:`wait`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_UNCOLOR",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4507,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "TYPE_COLOR",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4508,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "TYPE_COLOR_TOP",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4509,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "TYPE_COLOR_BOTTOM",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4510,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "TYPE_COLOR_LASTMUL",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4511,
	            "command": "chara_contrast",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4512,
	            "command": "chara_saturation",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4513,
	            "command": "chara_brightness",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4514,
	            "command": "wait",
	            "args": [
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
