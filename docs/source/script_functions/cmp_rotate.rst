.. _cmp_rotate:

cmp_rotate
========================

.. code-block:: text

	cmp_rotate(CID, sec, rotate)


Arguments
------------

* CID
* sec
* rotate

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def cmp_rotate(CID, sec, rotate):
		chara_act_complete(CID, sec, -1.0, -1.0, -1.0, -1.0, rotate)

References
-------------
* :ref:`chara_act_complete`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "cmp_rotate",
	    "args": [
	        "CID",
	        "sec",
	        "rotate"
	    ],
	    "commandList": [
	        {
	            "row": 4590,
	            "command": "chara_act_complete",
	            "args": [
	                "CID",
	                "sec",
	                "-1.0",
	                "-1.0",
	                "-1.0",
	                "-1.0",
	                "rotate"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
