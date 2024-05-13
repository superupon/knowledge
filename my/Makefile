resume_chn: resume resume_eng
	mv resume_chn.pdf YuchenZhang_chn.pdf

resume_eng: resume
	mv resume_eng.pdf YuchenZhang_eng.pdf

resume: 
	xelatex resume_chn.tex && xelatex resume_eng.tex 

clean:
	rm *.pdf *.log *.out *.aux

