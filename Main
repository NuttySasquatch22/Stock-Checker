using AlphaVantage.Net.Common.Intervals;
using AlphaVantage.Net.Common.Size;
using AlphaVantage.Net.Core.Client;
using AlphaVantage.Net.Stocks.Client;

using var client = new AlphaVantageClient("api key here");
using var stocksClient = client.Stocks();
var quote = await stocksClient.GetGlobalQuoteAsync("Stock here");
Console.Write("The current price of PBF is: ");
Console.Write(quote?.Price);   
