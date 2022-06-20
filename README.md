# Pocketmine-help

<h3>Entity Events</h3>

<a href="#motion">EntityMotionEvent</a>

# Motion 

<p>É importante colocar a namespace do evento</p>

```php
use pocketmine\event\entity\EntityMotionEvent;
```

<p>Agora um exemplo</p>

```php
public function onMotion(EntityMotionEvent $event) {
  $entity = $event->getEntity();

  $this->getLogger()->info($entity);
}
```

<p>Para saber qual entidade chamou o evento basta usar o método getEntity()</p>
