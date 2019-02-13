# my-issues

### Ubuntu 18.04 dock show on lock screen

```console
$ sudo mv /usr/share/gnome-shell/extensions/ubuntu-dock@ubuntu.com ~/
```
*credit* https://github.com/micheleg/dash-to-dock/issues/649

### Sequelize Join
var pk = 1
let models = await models.FirstModel.findByPk(pk, {
        include:[{
            model: models.SecondModel,
            through: 'TableThatManyToManyRelation',
            as: 'named',
            attributes: {
                exclude: ['updated_at', 'created_at']
            },
            foreignKey: 'first_id',
        }]
    })
