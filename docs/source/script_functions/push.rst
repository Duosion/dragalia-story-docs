.. _push:

push
========================

.. code-block:: text

	push(A, CID)


Arguments
------------

* A
* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if A == "0":
		c_push_t(CID)
	elif A == "1":
		c_push_t_slow(CID)
	elif A == "2":
		c_push_b(CID)
	else:

References
-------------
* :ref:`c_push_t`
* :ref:`c_push_t_slow`
* :ref:`c_push_b`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "push",
	    "args": [
	        "A",
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 26,
	            "command": "if",
	            "args": [
	                "A",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 27,
	            "command": "c_push_t",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 28,
	            "command": "elif",
	            "args": [
	                "A",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 29,
	            "command": "c_push_t_slow",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 30,
	            "command": "elif",
	            "args": [
	                "A",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 31,
	            "command": "c_push_b",
	            "args": [
	                "CID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 32,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 33,
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
