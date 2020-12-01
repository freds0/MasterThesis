# Master Thesis

This repository contains all the latex files for my master's thesis at UFLA in Computing Science (Computational intelligence). 

- Master Thesis (in portuguese): https://github.com/freds0/MasterThesis/blob/main/dissertacao.pdf
- Source code: https://github.com/freds0/HighPrecisionAdaptiveMesh

## Abstract
Title: An Evaluation of Mesh Movement Based on Laplacian Formulation in the Resolution of the Heat Equation by Discretizations of Finite Volumes with Delaunay Refining

Author: Frederico Santos de Oliveira

Abstract: In this paper we apply a scheme, combining the refinement and delaunay meshing in finite volume solution of the heat equation. We use the algorithm Green e Sibson (1978) to generate the initial mesh, the algorithm Ruppert (1995) to perform adaptive refinement algorithm and Üngör (2004), Üngör (2009) to make improvements on mesh quality. We move the vertices to great variability regions using a new proposed monitoring function based on the Laplacian smoothing, which is responsible for guiding the movement of the vertices. We compare the new proposed monitoring function with four other monitor functions, also based on the Laplacian smoothing that we find in the literature. The comparative results show that the new proposed monitoring function, while not requiring the least computational effort compared to the others, has the lowest amount of end vertices. All procedures for the experiments are detailed throughout this work.


## Resumo

Uma Avaliação de Movimento de Malhas baseado na formulação Laplaciana na Resolução da Equação do Calor por Discretizações de Volumes Finitos com Refinamento de Delaunay

Autor: Frederico Santos de Oliveira

Resumo: Neste trabalho, realiza-se a aplicação de um esquema, combinando o refinamento de delaunay e malhas móveis por volumes finitos na solução da equação do calor. Utiliza-se o algoritmo de Green e Sibson (1978) para geração da malha inicial, o algoritmo de Ruppert (1995) para realizar o refinamento adaptativo e o algoritmo de Üngör (2004), Üngör (2009) para realizar melhorias na qualidade da malha. Movimenta-se os vértices para regiões de grande variação por meio de uma nova função monitora proposta, baseada na suavização laplaciana, que é responsável por guiar o movimento dos vértices. Compara-se a função monitora proposta com outras quatro funções monitoras, também baseadas na suavização laplaciana, presentes na literatura. Os resultados comparativos mostram que a nova função monitora proposta, mesmo não demandando o menor esforço computacional em relação às demais, apresenta a menor quantidade final de vértices. Todos os procedimentos para realização dos experimentos são detalhados ao longo deste trabalho