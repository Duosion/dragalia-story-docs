.. _cmp_scale:

cmp_scale
========================

.. code-block:: text

	cmp_scale(CID, sec, scaleX, scaleY)


Arguments
------------

* CID
* sec
* scaleX
* scaleY

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def cmp_scale(CID, sec, scaleX, scaleY):
		chara_act_complete(CID, sec, -1.0, -1.0, scaleX, scaleY)

References
-------------
* :ref:`chara_act_complete`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "cmp_scale",
	    "args": [
	        "CID",
	        "sec",
	        "scaleX",
	        "scaleY"
	    ],
	    "commandList": [
	        {
	            "row": 4586,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "sec",
	                "-1.0",
	                "-1.0",
	                "scaleX",
	                "scaleY"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
