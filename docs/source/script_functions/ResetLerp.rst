.. _ResetLerp:

ResetLerp
========================

.. code-block:: text

	ResetLerp(SEC, CAMERA)


Arguments
------------

* SEC
* CAMERA

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "ResetLerp",
	    "args": [
	        "SEC",
	        "CAMERA"
	    ],
	    "commandList": [
	        {
	            "row": 5118,
	            "command": "blur",
	            "args": [
	                "false",
	                "SEC",
	                "1.0",
	                "1.0",
	                "CAMERA"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5119,
	            "command": "bloom",
	            "args": [
	                "CAMERA",
	                "SEC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5120,
	            "command": "color_adjustment",
	            "args": [
	                "CAMERA",
	                "SEC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5121,
	            "command": "post_film",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "filmMode_Lerp",
	                "-1",
	                "0.0"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`blur`
* :ref:`bloom`
* :ref:`color_adjustment`
* :ref:`post_film`
