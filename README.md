# Stock Price Technical Indicator

This repo contains the source code for the Stock Price Techncial Indicator Application. It uses C++ to create an algorithm that analyze the stock market to predict the best trading entry. 

It does so by pulling information from the stock market and calculating common indicators such as simple moving and exponential moving average. 

## Dependencies 

This project utilizes Jsoncpp and Libcurl. To run this indicator, they can be installed from the links below: 

- Jsoncpp: https://github.com/open-source-parsers/jsoncpp
- Libcurl: https://curl.haxx.se/docs/install.html

## Running the Application 

1. Install the above dependencies and combine all the files in the repo locally on your machine.
2. Run the following command in the terminal - 

g++ *.cpp -std=c++11 -ljsoncpp -lcurl -o exa.out && ./exa.out -I/usr/local/Cellar/boost/1.67.0_1/include/boost/
