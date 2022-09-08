.. _KAMITE_OUT2_SLOW:

KAMITE_OUT2_SLOW
========================

.. code-block:: text

	KAMITE_OUT2_SLOW(CID, CID2)


Arguments
------------

* CID
* CID2

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def KAMITE_OUT2_SLOW(CID, CID2):
		NO_EMO(CID)
		NO_EMO(CID2)
		mnu(CID, true, 0.8, 120, 0, EaseInSine, 0.8, 1, 1, 0, 0.8, 0, 0, 0.8, 0, 1)
		mnu(CID2, true, 0.8, 120, 0, EaseInSine, 0.8, 1, 1, 0, 0.8, 0, 0, 0.8, 0, 1)
		wait(0.8)
		chara_visible(CID, false)
		chara_visible(CID2, false)

References
-------------
* :ref:`NO_EMO`
* :ref:`mnu`
* :ref:`wait`
* :ref:`chara_visible`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "KAMITE_OUT2_SLOW",
	    "args": [
	        "CID",
	        "CID2"
	    ],
	    "commandList": [
	        {
	            "row": 2865,
	            "command": "NO_EMO",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2866,
	            "command": "NO_EMO",
	            "args": [
	                "CID2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2867,
	            "command": "mnu",
	            "args": [
	                "CID",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2868,
	            "command": "mnu",
	            "args": [
	                "CID2",
	                "true",
	                "0.8",
	                "120",
	                "0",
	                "EaseInSine",
	                "0.8",
	                "1",
	                "1",
	                "0",
	                "0.8",
	                "0",
	                "0",
	                "0.8",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2869,
	            "command": "wait",
	            "args": [
	                "0.8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2870,
	            "command": "chara_visible",
	            "args": [
	                "CID",
	                "false"
	            ],
	            "end": 1
	        },
	        {
	            "row": 2871,
	            "command": "chara_visible",
	            "args": [
	                "CID2",
	                "false"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
