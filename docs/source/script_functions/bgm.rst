.. _bgm:

bgm
========================

.. code-block:: text

	bgm(cmd, BGM)


Arguments
------------

* cmd
* BGM

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "bgm",
	    "args": [
	        "cmd",
	        "BGM"
	    ],
	    "commandList": [
	        {
	            "row": 72,
	            "command": "if",
	            "args": [
	                "cmd",
	                "out"
	            ],
	            "end": 1
	        },
	        {
	            "row": 73,
	            "command": "stop_bgm",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 74,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "v_down"
	            ],
	            "end": 1
	        },
	        {
	            "row": 75,
	            "command": "set_volume",
	            "args": [
	                "0.5",
	                "0.5",
	                "BGM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 76,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "mute"
	            ],
	            "end": 1
	        },
	        {
	            "row": 77,
	            "command": "set_volume",
	            "args": [
	                "0",
	                "0.5",
	                "BGM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 78,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "v_def"
	            ],
	            "end": 1
	        },
	        {
	            "row": 79,
	            "command": "set_volume",
	            "args": [
	                "1.0",
	                "0.5",
	                "BGM"
	            ],
	            "end": 1
	        },
	        {
	            "row": 80,
	            "command": "endif",
	            "args": [],
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
* :ref:`stop_bgm`
* :ref:`set_volume`
