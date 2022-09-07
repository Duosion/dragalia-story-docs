.. _SHOUT_COM:

SHOUT_COM
========================

.. code-block:: text

	SHOUT_COM()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_COM",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3214,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3215,
	            "command": "SHOUT_0",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3216,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.5",
	                "1.5",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`set_camera_distortion`
* :ref:`SHOUT_0`
* :ref:`effect_shake_bg`
