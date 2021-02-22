# yfinance_u

# base.py 353行目付近
# get fundamentals
# data = utils.get_json(url+'/financials', proxy)    ←デフォルトプログラム。マスクします。
url = "{}/{}/financials".format(self._scrape_url, self.ticker)   # 追加
data = utils.get_json(url, proxy)                                # 追加
