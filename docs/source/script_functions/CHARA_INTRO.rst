.. _CHARA_INTRO:

CHARA_INTRO
========================

.. code-block:: text

	CHARA_INTRO(CID, NAME, ANOTHER, ANOTHER_RUBY, AFFLIATION, AFFLIATION_RUBY, EMBLEM_NAME)


Arguments
------------

* CID
* NAME
* ANOTHER
* ANOTHER_RUBY
* AFFLIATION
* AFFLIATION_RUBY
* EMBLEM_NAME

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "CHARA_INTRO",
	    "args": [
	        "CID",
	        "NAME",
	        "ANOTHER",
	        "ANOTHER_RUBY",
	        "AFFLIATION",
	        "AFFLIATION_RUBY",
	        "EMBLEM_NAME"
	    ],
	    "commandList": [
	        {
	            "row": 5260,
	            "command": "chara_intro",
	            "args": [
	                "CID",
	                "NAME",
	                "ANOTHER",
	                "ANOTHER_RUBY",
	                "AFFLIATION",
	                "AFFLIATION_RUBY",
	                "EMBLEM_NAME"
	            ],
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
* :ref:`chara_intro`
