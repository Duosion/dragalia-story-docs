.. _SHOUT_COM_EFF:

SHOUT_COM_EFF
========================

.. code-block:: text

	SHOUT_COM_EFF()


Arguments
------------


Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def SHOUT_COM_EFF():
		set_camera_distortion(cameraType_Chara, true, EFF_007)
		SHOUT_0_EFF()
		effect_shake_bg(12, 0.5, 1.5, 1)

References
-------------
* :ref:`set_camera_distortion`
* :ref:`SHOUT_0_EFF`
* :ref:`effect_shake_bg`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SHOUT_COM_EFF",
	    "args": [],
	    "commandList": [
	        {
	            "row": 3226,
	            "command": "set_camera_distortion",
	            "args": [
	                "cameraType_Chara",
	                "true",
	                "EFF_007"
	            ],
	            "end": 1
	        },
	        {
	            "row": 3227,
	            "command": "SHOUT_0_EFF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 3228,
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

Sample
-------------

.. code-block:: json

	{}
