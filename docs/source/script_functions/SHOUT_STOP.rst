.. _SHOUT_STOP:

SHOUT_STOP
========================

.. code-block:: text

	SHOUT_STOP()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHOUT_STOP():
		wait(1.0)
		set_BG_effect_trigger(1)
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
	    "name": "SHOUT_STOP",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3220,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3221,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3222,
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
