# Async_Task
steps-
       1) Create a class as child of AsyncTask , which is abstract class having an abstract method doInBackground()
       2) major methods in AsyncTask 
                            -onPreExecute()
                            -doInBackground()
                            -onPostExecute()
       3) in Activiy class write following code
                        AsyncTask_class a1 = new Asynctsk_class();
                        a1.execute();
       4) if we executing asynctsk on Activity thread
                      StrictMode.ThreadPolicy policy= new StrictMode.ThreadPOlicy.Builder.permiAll().BUild();
                               StrictMode.setThreadPolicy(policy);
