.. _CHARA_SHIMOTE_FAST_SE:

CHARA_SHIMOTE_FAST_SE
========================

.. code-block:: text

	CHARA_SHIMOTE_FAST_SE(eye, lip, POS, CID, int, SE)


Arguments
------------

* eye
* lip
* POS
* CID
* int
* SE

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def CHARA_SHIMOTE_FAST_SE(eye, lip, POS, CID, int, SE):
		play_sound(SE)
		wait(1.0)
		BGMTUNE_DOWN_0(SE)
		CHARA_SHIMOTE_FAST(eye, lip, POS, CID, int)

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`
* :ref:`CHARA_SHIMOTE_FAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_SHIMOTE_FAST_SE",
	    "args": [
	        "eye",
	        "lip",
	        "POS",
	        "CID",
	        "int",
	        "SE"
	    ],
	    "commandList": [
	        {
	            "row": 1898,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1899,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1900,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1901,
	            "command": "CHARA_SHIMOTE_FAST",
	            "args": [
	                "eye",
	                "lip",
	                "POS",
	                "CID",
	                "int"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
