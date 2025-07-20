<h1> The Humble Programmer </h1>

<h2> Overview </h2>
This is a Turing lecture that Dijsktra gave in 1972. In it, he gives some brief biographical information about his start as a programmer/software engineer. 

Before presenting any arguments around the challenges that programming/software engineering faces, he mentions two opinions about programming from before-days:

(1) That a very competent programmer should be puzzle-minded and be fond of clever tricks. 

(2) 'Programming was nothing more than optimizing the efficiency of the computational process'.

The second opinion was the result of viewing the equipment as bad - the idea was that once the equipment improved, the problems of programming would be gone. This, of course, neglects the human element (my statement, for now, not Dijkstra's). He points out that the opposite of this result came about. More powerful machines came about, and we had a software crisis.

He diagnoses this crisis as having a minor and a major cause.

Minor: Modern machinery is more difficult to handle than older machinery.

Major: As power of machines grew, so did human's desire to do more complex things with them. The complexity of the programmes sprawled out, and we as humans struggled to write programmes that reduced this complexity. 

Then, we had even more complex computers in mid 1960s. 

Major developments in software:

(1) EDSAC in Cambridge, England, introduces the notion of the closed subroutine. This is essentially equivalent to functions/methods that we have now. It's so important because it 'caters for the implementation of one of our basic patterns of abstraction'. 

(2) Birth of FORTAN. Sees it as instantiaing bad habits into programmers. 

(3) Birth of LISP

(4) ALGOL 60. The report on this seen as a successful effort to carry abstraction a step further and defining a programming language in an implementation-independent way. 

(5) Pl/1 programming language. Frightening size and complexity.

He discusses a vision: that in the next 10 years, (before 1980), we shall be able to design and implement far greater and better systems, which will be of higher quality (bug-free). Dijkstra is sceptical of this but thinks that three major conditions must be fulfilled for this to take place:

First: World at large must recognise the need for change. He sees this as met, since 'it is now generally recognised that the design of any large sophisticated system is going to be a very difficult job'. 

Second: The economic need for it must be sufficiently strong. He thinks this has been satisfied.

Third: The change must be technically feasible. 

Since he gives quick arguments in conclusion to the first two parts, the remaining part of the essay is spent on the Third part. For this, he gives six arguments as to why this is technically feasible.

(1) As the programmer only needs to consider intellectually manageable programmes, the alternatives he is choosing between are much easier to cope with.

(2) As soon as we have decided to restrict ourselves to the subset of intellectually manageable programmes, we have achieved, once and for all, a drastic reduction of the solution space to be considered.

(3) Programme testing can catch bugs, can can't prove their absence. 'The only effective way to raise the confidence level of a programme significantly is to give a convincing proof of its correctness'. 'If one first asks oneself what the structure of a convincing proof would be and, having found this, then constructrs a programme satisfying the proof's requirement, then these correctness concerns turn out to be a very effective heuristic guideline'. 

(4) Designing programmes around the concept of abstraction. The purpose of abstracting is not to be vague, but to create a new semantic level in which one can be absolutely precise. 

(5) To do with the influence of the tool we are trying to use upon our own thinking habits. 'The competent programmer is fully aware of the strictly limited size of his own skull; therefore he approaches the programming task in full humility, and among other things he avoids clever tricks like the plague'. 

Just because a programming language has many capabilities and allows the user to do more, it doesn't mean it's good. In fact, quite the opposite often. 

(6) Hierarchical systems and factored solutions: Dijkstra argues that "hierarchy" is a key concept for all systems embodying a nicely factored solution. He makes "an article of faith" that "the only problems we can really solve in a satisfactory manner are those that finally admit a nicely factored solution."

While this view of human limitations might seem depressing, Dijkstra sees it as liberating: "The best way to learn to live with our limitations is to know them." When we are modest enough to attempt only factored solutions (because other efforts escape our intellectual grip), we will do our utmost to avoid interfaces that impair our ability to factor the system helpfully. This will repeatedly lead to discovering that initially intractable problems can be factored after all.

<h2> Philosophical Conclusion </h2>

Dijkstra concludes with a profound reflection on the unprecedented nature of the programming challenge. Computers have been with us for a quarter century, and while their impact as tools will be "but a ripple on the surface of our culture," their influence as an intellectual challenge will be far more profound - "without precedent in the cultural history of mankind."

He explains that hierarchical systems have the property that something considered as an undivided entity on one level becomes a composite object on the next lower level of detail. The natural grain of space or time decreases by an order of magnitude as we shift attention between levels. We understand walls in terms of bricks, bricks in terms of crystals, crystals in terms of molecules, etc.

The computer's unique challenge: In programming, our basic building block has a time grain of less than a microsecond, but our programs may take hours of computation time. Dijkstra knows of "no other technology covering a ratio of 10^10 or more." The computer, by virtue of its fantastic speed, "seems to be the first to provide us with an environment where highly hierarchical artifacts are both possible and necessary."
This confrontation with the programming task is so unique that "this novel experience can teach us a lot about ourselves. It should deepen our understanding of the processes of design and creation, it should give us better control over the task of organizing our thoughts. If it did not do so, to my taste we should not deserve the computer at all!"

The central lesson: "We shall do a much better programming job, provided that we approach the task with a full appreciation of its tremendous difficulty, provided that we stick to modest and elegant programming languages, provided that we respect the intrinsic limitations of the human mind and approach the task as Very Humble Programmers."
