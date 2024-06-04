# c2t_trainer

Kolmafia script written in ASH to train people with your [crimbo training manual](https://kol.coldfront.net/thekolwiki/index.php/Crimbo_training_manual) if they send you the kmail message `trainme`.

## Installation

Can be installed via the KoLmafia CLI:
* `git checkout https://github.com/C2Talon/c2t_trainer.git master`

## Usage

While it can run on its own, ideally it would be `import`ed, or called with `cli_execute()`, in another script that you run maybe once a day or so, such as a login script or breakfast script, so it can train without any further input should someone send you a kmail with the correct message.

### `import`

Once you `import` it into another script, `c2t_trainer()` can be used to do the training; there is no `return` value.

### `cli_execute()`

If you don't want to `import` it, you can still run it in another script with `cli_execute("c2t_trainer")`.

