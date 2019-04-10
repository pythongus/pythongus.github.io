Module grfc.game
================
Modules and functions used in the statistics calculations.

grfc.game.game_data
-------------------

.. automodule:: grfc.game.game_data
   :members:

grfc.game.play_time
-------------------

.. automodule:: grfc.game.play_time
   :members:

grfc.game.play_time_support
---------------------------

.. automodule:: grfc.game.play_time_support
   :members:

grfc.game.remote_handler
------------------------

.. automodule:: grfc.game.remote_handler
   :members:
   :no-undoc-members:

   .. function:: grfc.game.remote_handler.spreadsheet_data(ranges_names, spreadsheets=all_spreadsheets(), spreadsheet_id=SPREADSHEET_ID)

      Fetches a specific data range in a specific spreadsheet.

      :param list ranges_names: The named ranges in the spreadsheet to fetch data from.
      :param spreadsheets: The spreadsheet objects 
         from Google Sheets. Default value comes from function *all_spreadsheets*.
      :type spreadsheets: `googleapiclient.discovery.Resource <https://googleapis.github.io/google-api-python-client/docs/epy/googleapiclient.discovery.Resource-class.html>`_
      :param str spreadsheet_id: The alphanumeric ID of the Google Sheet.
 
grfc.game.season_history
------------------------

.. automodule:: grfc.game.season_history
   :members:
