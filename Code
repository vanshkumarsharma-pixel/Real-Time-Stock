import tkinter as tk
from tkinter import messagebox
import yfinance as yf
def get_stock():
symbol = entry.get().upp
    
Company : {info.get('longName', 'N/A')}

Current Price : {info.get('currentPrice', 'N/A')}

Previous Close : {info.get('previousClose', 'N/A')}

Open Price : {info.get('open', 'N/A')}

Day High : {info.get('dayHigh', 'N/A')}

Day Low : {info.get('dayLow', 'N/A')}

Market Cap : {info.get('marketCap', 'N/A')}
"""
        )
    except:
messagebox.showerror("Error", "Invalid Stock Symbol")
root = tk.Tk()
root.title("Real-Time Stock Market Dashboard")
root.geometry("500x400")
title = tk.Label(root, text="Stock Market Dashboard", font=("Arial", 18, "bold"))
title.pack(pady=10)
entry = tk.Entry(root, font=("Arial", 14))
entry.pack(pady=10)
entry.insert(0, "AAPL")
button = tk.Button(root, text="Get Stock Data", command=get_stock)
button.pack(pady=10)
result = tk.Label(root, text="", justify="left", font=("Arial", 12))
result.pack(pady=10)
root.mainloop()
