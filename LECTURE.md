# Set up a venv


- @app.route('/')  @ is a decorator   - default landing page, include the '/' in the URL
def home():
    return "Hello, Flask!"                               # return a string


if __name__ == '__main__':
    app.run(debug=True)                                   # run the Flask app # http://127.0.0.1:5000 shows in bottom - go to it in browser

    #Routing and Resource Handling

    1. #@app.route('/pokemon/<str:pokename>')        # some code to get the specific pokemon from our database
    2. #def pokedex(pokename):


    #Endpoints are the URL patterns that the application will respond to. 
    - endpoints are the target example is /cool 
    - Tools to access the database Marshmellow 