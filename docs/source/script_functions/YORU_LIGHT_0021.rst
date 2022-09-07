.. _YORU_LIGHT_0021:

YORU_LIGHT_0021
========================

.. code-block:: text

	YORU_LIGHT_0021(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "YORU_LIGHT_0021",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4493,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "2",
	                "238",
	                "255",
	                "255",
	                "1",
	                "0.12",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4494,
	            "command": "chara_color",
	            "args": [
	                "CID",
	                "0",
	                "3",
	                "99",
	                "182",
	                "218",
	                "1",
	                "0.12",
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4495,
	            "command": "chara_contrast",
	            "args": [
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4496,
	            "command": "chara_saturation",
	            "args": [
	                "CID",
	                "1.05"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4497,
	            "command": "chara_brightness",
	            "args": [
	                "CID",
	                "1.03"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4498,
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

References
-------------
* :ref:`chara_color`
* :ref:`chara_contrast`
* :ref:`chara_saturation`
* :ref:`chara_brightness`
* :ref:`wait`
