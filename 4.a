class Queue:
    def __init__(self):
        self.queue=[]
    def is_empty(self):
        return len(self.queue)==0
    def enqueue(self,item):
        self.queue.append(item)
    def dequeue(self):
        if self.is_empty():
            raise IndexError("Queue is empty")
        return self.queue.pop(0)
    def size(self):
        return len(self.queue)
    def peek(self):
        if self.is_empty():
            raise IndexError("Queue is empty")
        return self.queue[0]
q=Queue()
q.enqueue(10)
q.enqueue(20)
q.enqueue(30)
print("Queue after enqueuing elements:",q.queue)
print("Dequeue elements:",q.dequeue())
print("Queue after deenqueuing elements:",q.queue)
print("Front element:",q.peek())
print("Queue size:",q.size())
