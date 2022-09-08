.. _CHARA_KAMITE_FAST_SE:

CHARA_KAMITE_FAST_SE
========================

.. code-block:: text

	CHARA_KAMITE_FAST_SE(eye, lip, POS, CID, int, SE)


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

	def CHARA_KAMITE_FAST_SE(eye, lip, POS, CID, int, SE):
		play_sound(SE)
		wait(1.0)
		BGMTUNE_DOWN_0(SE)
		CHARA_KAMITE_FAST(eye, lip, POS, CID, int)

References
-------------
* :ref:`play_sound`
* :ref:`wait`
* :ref:`BGMTUNE_DOWN_0`
* :ref:`CHARA_KAMITE_FAST`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_KAMITE_FAST_SE",
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
	            "row": 1870,
	            "command": "play_sound",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1871,
	            "command": "wait",
	            "args": [
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1872,
	            "command": "BGMTUNE_DOWN_0",
	            "args": [
	                "SE"
	            ],
	            "end": 1
	        },
	        {
	            "row": 1873,
	            "command": "CHARA_KAMITE_FAST",
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
