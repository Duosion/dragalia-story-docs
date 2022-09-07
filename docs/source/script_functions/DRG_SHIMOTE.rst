.. _DRG_SHIMOTE:

DRG_SHIMOTE
========================

.. code-block:: text

	DRG_SHIMOTE(eye, lip, POS, CID)


Arguments
------------

* eye
* lip
* POS
* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "DRG_SHIMOTE",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 1963,
	            "command": "play_sound",
	            "args": [
	                "SE_136"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1964,
	            "command": "wait",
	            "args": [
	                "0.3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1965,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.1",
	                "0.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1966,
	            "command": "wait",
	            "args": [
	                "0.7"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1967,
	            "command": "effect_shake_bg",
	            "args": [
	                "12",
	                "0.1",
	                "0.2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1968,
	            "command": "CHARA_SHIMOTE_SLOW",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1969,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 1970,
	            "command": "wait",
	            "args": [
	                "1.5"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`effect_shake_bg`
* :ref:`CHARA_SHIMOTE_SLOW`
* :ref:`SEFOUT_DEF`
