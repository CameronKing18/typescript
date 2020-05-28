# TypeScript

Крупные приложения сложно писать на языках без статической типизации. Поэтому в мире веб-разработки появился и полюбился большинству разработчиков TypeScript. 

Пройдя этот блок, ты:
- узнаешь базовые принципы работы TS
- научишься писать на TS
- научишься использовать TS с React

Этот курс ориентирован в первую очередь на новичков в TypeScript. Не жди, что он раскроет все сокровенные тайны TS.

## Необходимые знания

Курс предполагает, что ты уже знаешь JavaScript ES2015+.

Для большей части курса знание React не нужно. Но курс описывает работу TS+React. Поэтому желательно знать React. Для этого можно пройти [курс](https://github.com/kontur-courses/react).

## Самостоятельное изучение

Вся информация из этого курса зафиксирована в этой [книге](https://race-timo.gitbook.io/typescript/).

## Презентация

[Ссылка на презентацию](https://kontur-courses.github.io/typescript/#/)


## Ссылки на задачи
В процессе курса в презентации будут ссылки на задачи. Чтобы не нужно было их искать по всей презентации, дублируем ссылки здесь:

- [Простые типы](https://www.typescriptlang.org/play/?strictNullChecks=false#code/PQKgsAUABDWOgggGEECwgDCcIFQQiCA4QQ-CBcOwgCgYiBaByIFFlPoLwgCg4iCCsINVoPIgUSg3CBsCGANFACN+AYwpQAJvwwJAXCD86GQHwggRhBA0iCRYUagyhqOiqIsASIFmWKZUGYsA8IHi4ksAOkghgkSMID2AOwDOAFyhuKABeKAAzbgAbXwBTAG4PHwDBUIjouMSILz9A0TDImISk3Ik0wsz3CBKUgEcARjTuLJy6gCY08QBtAAYAXRbkwNqAZjTajoBqKAaoafFHKNjvAHN-AAtB0tqAFjSBReW19bnBLra+w9WNrbqAVn3QkLDhLvq+3oGa4YA2NNf3p8ni83h9+p9bsMAOzjP7PMK1B7wqAAj7vSEzAAcAC4oN4AK5RKL-CFAA)
- [Тест «Типы как множества»](https://docs.google.com/forms/d/e/1FAIpQLSdoEt54rr4l0UZaxu9GnlUVC-KOwNt7yYgyGAxCok3X2FX80A/viewform?usp=sf_link)
- [Тест «Объекты»](https://docs.google.com/forms/d/e/1FAIpQLSc8imy1IR8rPN5z4pMdmlYNJnKks0NMdNnh3OnjFMqvVkf0Jw/viewform?usp=sf_link)
- [Тест «Функции»](https://docs.google.com/forms/d/e/1FAIpQLScVFtG0snYPZ60B9nP5AEKOjSo4n_dKAOsmVCeU1q0k4WmTZA/viewform?usp=sf_link)
- Задачки практики середины курса:
    - [Задание #1](https://www.typescriptlang.org/play/index.html#code/PQKgsAUABDWLgghhEEGwgheEEHwgVBCIIDhBD8INwdhBtABEDUCYQQBhBNAZECmxU0FYQYwERBHBOEEEEQKAYQEMANgGMArgL4AXAPYAnADRYKgLhAFgcRBMaQIwggaRAoZbQXK6ABkMGjx0mcag7A3CDYokWFG5pAEiDZNSioB4QR0povvh2gPIggGIg2I7YDraMBFAo2ICiIHpQBBRk2JzYvmicOFBomFC4zIyALCAUKCjaqbgUxH6MmKRkAHTOsIBEIHi6AMoiALYAgkISAJZSAHYKADIAptMA5hIAFmOTMwoAWgsyUptT04pKSIxQeagYvowooTSdECDAkJASAJ4ADgtQg6PjY5QAC8UAAFO1IV8+DI+EMAM4ALigfGmHwAlCCAHwotEAbne31+ixW6yOMxB4Mh7WhsIRyNRGOxuI+BIgnx+UD2B3JJ1BEKhMLhSJZmOBOMZbI5xKky15lIFNKF9NFzMVtOFDLRYol+LeEAm0wk+wAZnwhL9+MIxJJZFAAN5dGBgoRSIZDVEAE2R8IkMkNy3RyP+vLZLhdbo9029UF9-pWQagJNWG0BMzDsAj7q9Pr9AcT3MOaemGedruz0dz8cDyLmstDkAAvvrQFBALQgGhKgQqWFIgGYQKi0FAXFDIdBQF6QV3TX1QMzWyyyZFWiy2mQK8tRmNx-Naj7Mx3QWDwgDuEwkQjW4M3Xsxh5cLjM8N+ACJ4cMX4inQ+XDIFhIRBkE4wT4PcFAAIz3HUUSgABqKBwNLB8n1fAQlhTT9vx-GA-wAoDwVA1VxRRdo0NJNYkMfPhnygF8AC99ikTCj2w2BcMA4DCMZaDpSkE0YOBQTaJ3FYXygAB+EiyJTKAAEIhIABigBk5MUyjYBQ2iBFlZjWN-f8OPBSCiJxECoOZABZSQ1lI2UQMxYAoCs9ZbOWMFwPRb9mwgbzWwAWgCidXggSBW0ARBB4iKTxNDQJQgqncwbSsME3w-dEwQARgUhQMoAVk8iB51XZKX2k9YX3Sl8AEcTwWGq6oqhKFzXFKGIOCrMoUgqiqS2RWsYjrqtq+rGsKmZZwEPk50SxcZBS7Tlg65ybIAUQKybMvyprir60qdPSgAmQ7coANgK8LIo8LxYvikKIFbQBCECirwfH8W6etm+bBD4ABrPhBo9cQ-tG7berm1Khg6v0RAWbqZpaiGOqyuHmpK99IcqjKQcK+GSrKtYka60HPtK9DyvS6HYeJhH8cG-6FBfcDsY+hG2qY9KspyomcdR3a2cJhmstGlmSv5zGFJfLmUZ28GxbBSnpbB-r2vS+1G0Vkm5YAbQAXQK6m8f2lKFmF3HdoWwahY1mmjYVg3zaN5GUqyiXrcNxaOa6+WZBht2HY9sEDq5g6ABZzpAKAAr8oKgA)
    - [Задание #2](https://www.typescriptlang.org/play/#code/PQKgsAUABDWCgggGEELwghpECkwrCCEEQQXCCD4QQbhBAZEHykHYQBQZhA9AhED0CYQAjJVQURAoAXATwAcBTKAEMANgEtBAZwB0UQPgggARBAHCBRA-CB5APCB5AkiDKki9gCIseQIwg85Aag1FKqAGUOAVwAmfAHYcpkWFECEIKYwlGgwrGzQAFT5BAGMACz4AJyhlABFRBL5ojgB7JMUyZPUMQDkQHVYsQHkQULV6GTgCKpV5BkCcZUUsNWIyQGEQQE4QYO9YFUCMIpYUEPooLARNdXR8nplAHBA8QDYQJDwoPCaMQBYQDAaaInQGSeqUL2hYIZhImPi8oowaZMOka0AREEUcBDp5AAaQoVYE9Zr0ZinXCKAgIZIzAgMBDyU75KAYahQHDg4y1O5QQBIIIjkfIQjj5HioA84okALTwtTYgjFQDiID0oKJnNjcfCmOtFG9TIApEAwODeWHezG+v3+eGaCwps0BBKQCDI9GQijGCOaxGKUB6rMFRwq1wJaQyWVyhQwryln0UPz+AOBinUoJJmtRMxoPQ+dGmyiwSO9pyNJqYfRkvlDKKIBKwfoDDFU2y5vv90vhxkO8gFQpMovFMwdMpd8o0CPdzB1SaznwQ1x8sdJ4eNwSjac53IjnaqucCBZ2RbFErLTtlAI0bvGYzBEMw6gJyjwgDEQZj4PqGjumyAgYCQbj8KAAVQkiSgAF4oABvAlcgBcUAkHASojcAHMANwEtyCABbPhn1fd8v1-CAAF9ICPXgBAAYWyRwEgva87wfZxnzcRwAIAI0SCCfA4UQOGEYCXzfD8f0gaCIFgk8AHUSNiAAlQQOAEG97xuGAEnY8iAEYoAAHygAAmESoAAZkkgAWSSAFYINo+iBCYjhYgcFx3A4FjsjItDuJ8BJ9PIgxX20jwDBomCIGPNTmJpJ49IMriCRMsjnwMDjHkSayoNs+yoHU2IABk+AANz4YRDIJMiouELyACtHDcURcksUSDAArlnDIzKoHM9x0oSfzaNAKA6SqqAD0CuD7CcVwPEQ5DUJvFqUIEAAyYLmK0prdNMqAepCtiOOG3qNPChLVIayyODQ89Lx628oGiJDOokZ9VoAbSfKBsLwxIAF1n36nSOtQyCoBUuz6qcy8byWhI6pPS1MhyJInovBIIMgUBqrkCFWnhSq6VqiB1rcV8XwEs7Gp02KeJ7LyJAEgwVWR-8gNR9HMZ8dbWr4Lb0ORnwdoE07SZ8GnYH2gT8dpmniNIsyADF0lfDGCSZqA+I458FMZ3neNM1GEas4WRfi6KvJy5w8r4fzedonxIMx26oZhjg4epKJaS+6m6cwwqde5rHALMs2pZlxLCpStKMqlwnNu2nnYB2hSqaMkWYH2oX3dplnPMKjmADMNPN33RZD7z9aeZWmfVwOoAp72U58KQs7RqQXYvCQ06l3mPKt+O-JT1XYFozXsmhhbnF197rUNn2-ZNgwG6j2BsbMzupYsgaSdbmmdvM9GqbRouPfMsSDHTsmmf2meu99nvUdniuCWT5GfINoeU9Hs35+jqAs6kHWp9p-nyKky+brvw-Z+P6Ol44We758NfTffjPYFt1HipO1-rxfigtN7I2rrZCqVU6Q1WAEAA)
    - [Задание #3](https://www.typescriptlang.org/play/index.html#code/PQKgsAUABFgEIIrCCAYQQ3CCA4QQ7CCGEQQnCCCEQeUgIiCaC8IIFwggYiCqByIFALYCGA1gKYDKALiwA4A0UZQHwguQYAEQRIHkQKIH4QQTNHxALCCBpEEWZAkiDxAPCCYogQRBBekRJI0oqQMwgo5VEBMIIPS3x6xPFyQYe5EszVNBVDQoADsAVwAbcIA6OCQ0LDwCWz0CEnhBQEYQQFEQQUVULWUCRWQpNIJcVGllGMAMEHQM+AtERKgGYIBPKMgPKABxBjp2DgYuAC4emABaegZuKGmtRD09VFtzK0FbZSyoTMApEHgyETWACkBxEBEoQFkQS9xEIQJp00A2EHgASgn5qG5whnaWABOAAUAPYAZy+qEUhz0128WngJDu61EgjIiDsUEWy1WAQ2Wx2+0Ox0+0zBAGMQQCWF98GQNKhsPozm5SVAOKEAcEviRBAjRFA6RpGnIcopEN1oFAavjBEyiUcvjc5EZUej+EIROIpNJRKhTIs3LtFLzzOh9N41H5UDt0CRECzTNhRjA2QAiIFuyEbMjugCiXumTkQFndABlA-o0ajbKhNO6APqRvT2DK5e1SMjeXDoyUwQBYIIhniomWKUWioCcPW63jJlHc3HodfAFAijKhcIAZECbdl1iHsMUASCBQdD91ArLSGCq7XCCwQWQQa+5ynqWGNy3YZA6K+1ijs9vR92wY4Tl9XyQTjsUSWdeHzWgi69IZcToTaIUwScZSqZQQCoIF4qD6EeGIppk6aSAI2bopWbpJrW0xrhW0gtto8AuI2pSgam6a+FBbj0t+MDEVAADa1b8HBboALrzAAfGRVGUZ61EANykgBQSHuIx5RmQMZxgQVYRghZ5QA0Ci3tGmyCfwU6uLgB44SakFZgRiBESRjGepREa0ZMDHkTpUBUbRABkUAUlSNIALyWZS1JQAA1FAACM7E-vMnFAdx-YYsGFiwQGolIWQUCYBkqwKXY4gLnJRgKQe0mxpomkkUZbqUQG+mGRRJl6R5PQyuII73B+ZxRZhGrzuK3y-P8wLglANktTM3BROELDBAA5hwAAW8yuTEgAoICU1wiAuMysJwPBQIogjIM89o9LYLYkJgXYhBE0RFVYuiTktcijtImDtptZC8tIQhMgASqEwS1LKBAGEYggmKgBB6nomCYZiQgkAYaAxN5PSyLs-1nB+ZhrjYaz-YDQFpLOgiABIgqBpmF0x2g6HYohiCgoBg772nYa2CD0JyBEBwirbOsjzRY9poG8MSAGgg8DIIg+DIJ2vL8BcmSwwIRbzVoUC8vYYv9IMnAjCwkwEBkyjIOLmzKEyVxkOg2jSCUArYisx6rrKTLoqIuDVJAIDAJKHDtNwNLS0McvNa0HSSgAZvd5IcAAliC3KMNNXDcCcADedV-ICoJgvwjB8PZ1n8ByXJQAAvi6Tuy1wbyZwMztcFAAA+W2RFAYeQGnkqQKAkzTPmuSlSdegwTD8yTNbkCUsEYIcJZwwAhwACysyuxllFJhPmUmZPJkBlPWXT2688z0vEYL6vi8b26BVdwHvf9wwg-Zywecy8Mhd2RHVnUi6AAMcezC6vdH8Psz8D8UeNWC9-J5ywT33Th5TqfcX6X0PsfC+LAPLdwPiwAAHg7H2LAAAmAAVf+EI7IACYAAsMD959wQUgrgKC2AOVslAAAbIVCAJwvbBB9v7bk4QQQglDrWCunlYF92CAgjgJ9XZByGDwE4YCWBvA8iRX2HtKx8PgQIqBzVWphEiJwz4JFYEgk6h1EE3UTgAAMMGp0pPdDgLoAAkYdxFRBTsENOBiPieU0fvbRLBdH6IMeQ6yljrFQKiDfFgDjJEaOIjIysNi7FQAAIStWISwZB6DMHFxLjYwJMS4mIISaQ7xjki6pP8fHUiNj44dS6r1AakxXK0ViXZas6jnFaRgP1AEIIADuIQWAdL9ACVpAIqxsBBIMfqvtuRtNaT1GsUimnp1CTAakdjpkwCrtw1xOjySdSPicEJqye5uI8SceRii5ZRFKQAKxBKMqsNYnEkXEa7I5J8lmWRYBwNBvtBgglCBwE4rD2H8FcnfIFTi05vG2R5Wu0x27WyAA)
- Generics
    - [Тест](https://docs.google.com/forms/d/e/1FAIpQLSdlTz1EhwzoH7CLF9Wo-Jwy2v1qlErMTlnrCbllYwf0yXJlVQ/viewform?usp=sf_link)
    - [Задание #1](https://www.typescriptlang.org/play/#code/GYVwdgxgLglg9mABALxgBwBTBgJwM5QA0ieAphAgCYCUiA3gLABQiiFYBiAtjGADKkwAcygALRAF5EAWQCGYgHQ8wWXAQUAbQSNHEy7Spu1jqAbmat2nHKTwgNUSYgDaAXXMtEwODkQYtjjBOAAymiEEAPNy8AsJiYTAA1Im0jJ6sNnYOCmggeKIYztj4UM4wrnrkVGWurtQWiAC+DTZQIDhImfZQzM1MzFaOAI4AjABciACCODiyAJ4RzmAgXABGpDh6UDi8Qq4AfE6omM4jxABMxADMxAAsxACsxABsFS4ARCPvxO-n34jvK7vOoeQaIIbnCbTWYLZyrOBwLSyMDEeGI0jIg5HdCFbYgUhvIqyDRkYjAYlkEEDBB4dGaOBCDCjYgQsxAA)
    - [Задание #2](https://www.typescriptlang.org/play/#code/GYVwdgxgLglg9mABAcwE5xABwEIE8AUAzhqhAKYA0iA1mbgMpkA2Z0cqVAbgIZMhmMWbVAEpEAbwCwAKESIICQlESoyhEE2UBeRGDIB3RAFlumfCIDcMucHaJ8LZTEQ6ADBcTOAPImIhSZAB0LGDIUAAWHjAA1NFiUrJy8opOUGQAti6+JOQA2jAAulaJcgpgSjR0WbQMzKxQ7PgwaelUMJbWSWUVPHxkWb38gvWNzRltHSWewPYAhKrqmoHh3IT4NSLxnUkqahpQgYRkUOt0VLkFkzsAvtu7iwfIx6e4IoGYIITh+INkV4i3aSdVRQfxIBb7YqAmTdZQARwAjAAuYymLxgEDpABGZA4ukxONQFwAfFk0BgcARcgiqAAmKgAZioABYClQAB4uUmcgCkiHpiE5Wm5iGiiARk1hiDhtJRJkwXixcDgLG4YCo4nZKKUqBgoTaKIx2Nx1xJch05KweHwuQARNwHbaqLasa6nYhbRAIO7bXCfUxeNxqNxbWz7AB9CZczw82kuLRuKj4dlR4X2cQwDnXTYwxQqoJMODIfCIqgyyxAA)
- Классы
    - [Тест](https://docs.google.com/forms/d/e/1FAIpQLScGHVFdzcK747iP5ZToxucNWiFQSRcSrmwk6MC_nA9fQA7ZQQ/viewform?usp=sf_link)
    - [Задание №1](https://www.typescriptlang.org/play/#code/PQKgBAsAUGtouCCAYQQ-CCA4QQEiCsEIghWEDAYwBsBDAZ1LACEyBTaOMQDBBBBEGUD4QQbhBAZEEHYQQYRBAnCC4wgRhBOgLhBUYAESAsEDaAWEFE4eYNpjHjpYKXMVhmajeMSAeEFTaFHQPIgYZIAEQNoCYQHPclgsqND0SAxEFSo9HCA+CBszBx4ToDSIOwcgLwgOHGotuKKiGBOYKlxzJxSCpyAbCBxbKJRWFxggOIgqOGlACwADNAgwNDQoGDySiIqRqiaYK3QRGQUAIJgNAAeAC40AHYAJhTUpDRgAN5BsPgA9gukswBOAK74s3vHABTTAFxgC6cAtgBGNMcAlFs7DGCkpwADh9bgAaGTjaSfADcvwAvu0YHBAadXoQAJb4AjEQj4a4ATweTzeH0+RJe72OPyRfzAxxos1OxwWYFmAAt0aQAHTTMAAajA+NhNLACKgYpGJHIVCmc0WKyotGpDH2hxO50uN0J-xO6IWAHNvtsRQwAcCbgBGRrg-Ew+GIhgotGY7G4gnkklfZW0ukMpkswHEY7rACSC1m13ZnK5tv5guFDDFEqgqqOrvwpxImtIDzWNAA2gBdMAAXjA+YWNAA7mBxtcrZ9wZWa5RrtIrVDC8LU7N-i9S+nM8Rs1znsRAbdSwA+MDTLn4HF4ufTT6fLn0pbnGjXa7EcH4b4lmfEOMH7sHUh7Qg0LmEPb664A552qCdAC0H6GbSgHXA3QM-QiCY5hfiMi5Dtm+aNIWMbCs2irrPW1oyB2L7vp+rRAA)
     - [Задание №2](https://www.typescriptlang.org/play/#code/PQKgBAsAUGtouCCAYQQ-CCA4QQEiCsEIghWEDILhBBuEEUEEQEsADTFTC1WUoBUBPABwFNo4xAMEBOUB8IIUAyIIHYQQMIggThBcYQIwgQ-DQBEgLBABgFhA5OUWAGZ5+JdTCqNYcntSz8iQDwgqI+sKB5EDDJAAiADATCA53i2vSoooiAYiCoqFxwgPggAiSEeF6A0iCChIC8IDipqK74GohgXgQCqSRCNOpCgGwgqQJyiVjCYIDiIKhxNUoATAAMYACMAKxK0CDA0NCgYGqastq6+gL4YMPQAMYANgCGAM6blGAA3tAAvqNQAC5s7EwXYAC8YOsAdswA3CcAlg+n7ABOAGbry0uAEF9pFYAAPABcYAeAFcALYAIx+rygxyg0A+Xz+AMuACFQTA4KxvljoQAKZjQzanUkPADmAEpbgA+MAANwA9m8ACao9HQX6wh7LU5vTkPMDLb7sdZfclQmEI5HfAA0YHOHGhFBYHEZ0JBADIwASDkTYDLTrDvpKHuwAO4ai4Kxn8k7S2Xy-rqiiMgB0JKx5I6nSUjLG4AAtNHFiMMVA1lsdgB5U4ACx+hO4ywlNO+sNFnO+5NYsMRqzeyzAirhSJ+6tL5crYCpSrr32ZZu46IFUHGk3MsysNnssZWMrl7HJ3rAqYzHYjYGjkdjQA)
 - Полезные штуки
    - [Задание №1](https://www.typescriptlang.org/play?#code/PQKgBI6CCAwggsIFi8IIDhBCsIALgFBi2QBCDKoNwgig7CCDCIIJwggQiDJiAiIKfIFwggYiCKByIGAI5iVSMA0YQOIglQHwggRhBA0iBh4NKQVFhRgCRBE40YzCNRgHhBA-CCICgeRBWiMGb2jAgiAEagJhBJlgrKRHM2O1tHwroomHkoMGIoAytAGRAMbDAAIgBGAAYwAEsAZzAAU04AVwBDABt0gBcAezBEgDowACYAVhT0rLzCsFKa2qrqpLTMnILisq6Y9yxADBArJ3CyKhoigE8ABwywAHM8gCcAEwBaSUEScWRAZhAoGbAAY1zUot2K9BBgdHRkgDsijPWAM1zz5YBBMAAbxGYE+JRKqDAAApcpCXtkALYAIw+AEowABeAB8YHhyI+AG50ABfJ6vd5fH7LABCQJBYIh0NhuMRKPWgiRcNZaMxOLxbKJ0RKRQAFh9IVD0diWfj1kTSc83h9vr8wABhOnRJG5dYS5n8nnSg1yklPT7ZF7nIrJEovLgwyEAgA+YFpLrVqK5ss12HWGSK2XWdri8qeoDAgHwQQACIKI7Mgo4wgg90OdbdcuHFMfbAaDwXqvWypTjcmBiaiiamXunONUs5woTmGXqOUWwCWANRgJGCYVi3XQ1txeplitpopcADMdYbXZ1kJL0pLZaeldSJXyGQq+RKKyhAAMACSAzhxYkNXrNAblBJVI81s89Jr9VqDDpgO8Th+NPotNpdPflkAA)
    - [Задание №2](https://www.typescriptlang.org/play?#code/PQKgBI6CCAwggsIFi8IIDhBCsIALgFBi2QxCCEYQZQARBFAhEGTAEMA7ATzEGEQMExQfhBA+EECYQMAZQFcBbAGK8qAYwA0YAKIBHXhQA2AZ2FiwiMACUApgDdtAJ1HbVo9WDYtEgCRBS5RIFEQJlEBcIOMzZA4iAk2eQNIgYPDk-oDcIGwWtnhsLmAubIA8IFYhgPIggGIgiIgAdGCA+CBsgIIgIeQcfuwhQUjJsWxwYFxx8PlsIRowzYBsIPDh-iSAMiBgAMxg+YTRiBjYYABESgKSAEwArFMeWFPacopKkgAuBrzaU+6TUwZ6hsaSALQAjAAMKyDA6Og7NAAO2jwCpmAAvJRaABuV4fL6yeTKX4A6g0EFvT5ac5GEwiMww4EvBFfUxKf7fIRosAAH2kmyhRNJOn0KNMIPQADM0TsAJYAeyoYAZbLZAAoKKgwFQBAAjQySEWC4X8MUGSRMsRKQW4gCUYAA3qswEoAO4snaiAAWYF5CtESky2LVmsmk1EFCUXxmAimE1t7tEHKUbIU2kyCjZAHNec7+EcuWiLWb+RKVSqQe73SKzhQANYJxP2x3TDaQpSurWJsCeqje33+oMh3NbcNmqNomNgEVxjNFrDJ7Rp1u2rNOs404wFtvYEtlv0B4OnZGD+WRzLRihxwuJjtdrUAX3Qm8ZPN590kN0WknVYGxgtDtbRgsbzf+AD5KGAANRNsDr+M7vkDO6Sb-H09gue1bKJeYjXhQsb3o+fwwa+74gtyfL7mA9w-hqAGfOe-YXIcs5gdBD5XBQb7xkAA)
- *.d.ts
    - Написать файл декларации типов для файла [vector.js](https://gist.github.com/byTimo/c51bc16d8c48e676da840f3f892b14c6)

