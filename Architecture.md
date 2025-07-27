System Architecture

YouTube Videos or Financial News
↓
[Whisper] → [Transcription]
↓
[FinBERT] → [Sentiment Score]
↓
[Signal Generator / Feature Engineer]
↓
[ML or RL Strategy Engine] → Buy/Sell Decisions
↓
[Alpaca Broker API] → Trade Execution
↓
[Backtest Logs + Visualization]

Modules Used

- `Financial_bot.ipynb`: Whisper transcription + FinBERT sentiment
- `tradingBot.ipynb`: Reinforcement Learning via FinRL
- `learning_bot.py`: ML-driven strategy logic
- `lumibot_trend.py`: Trend strategy implementation with Lumibot
- `gld_signal.py`: Rule-based signal generator
- `config.py`: API keys and trading config

All components interact through a modular and extensible architecture.
