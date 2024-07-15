в useHttp.js в рядку 27

      } catch (e) {
        setError(e.message || "Something went wrong");
      }

      Розібратися, чому e.message видає об"єкт, а не повідомлення про помилку, порівняти з іншим проектом з кастомними хуками
