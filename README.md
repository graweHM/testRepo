# Priority Queues
This project implemets two basic types of priority queues:
<ol>
	<li>MutablePriorityQueues
		<ol>-The queue and it's elemets have changeable values.</ol>
	</li>
	<li>ImmutablePriorityQueues
		<ol>-The queue and it's elemets aren't changeable and have to be recreated with each change.</ol>
	</li>
</ol>
They each store elements which have a priority(int) and a atom(string).

The queues are sorted by priority with `priority = 1` being the highest.

Each Queue implemets the following functions:
<dl>
  <dt>`insert()`</dt>
  <dd>Adds a new Element to the queue.</dd>

  <dt>`next()`</dt>
  <dd>Returns the first element of the queue and also deletes it.</dd>
  
  <dt>`changePriority()`</dt>
  <dd>Changes the priority of an element to the given priority.</dd>
  
  <dt>`deleteElem()`</dt>
  <dd>Deletes an element from the queue.</dd>
  
  <dt>`merge`</dt>
  <dd>Merges two Queues to one. The Queues can both be from different types.</dd>
</dl>