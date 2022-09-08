.. _SHOUT_STOP_EFF:

SHOUT_STOP_EFF
========================

.. code-block:: text

	SHOUT_STOP_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	wait(1.0)
	set_BG_effect_trigger(2, 2, 1)
	set_camera_distortion(cameraType_Chara, false, EFF_007)

References
-------------
* :ref:`wait`
* :ref:`set_BG_effect_trigger`
* :ref:`set_camera_distortion`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_STOP_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3232,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3233,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "2",
	                "2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3234,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "false",
	                "EFF_007"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
